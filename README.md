# Welcome

Hi! 

This is a knowledge base (kb) vault template that you can use to bootstrap your own kb of notes.

By the way, I use Obsidian to work on my notes but you don't need to if you don't want to.
You can use whatever text editor that you like.
Obsidian happens to be really great at helping you manage and edit your notes in a way that is easy and it's just an all around nice experience.

It has 3 key folders:
- kb: the actual knowledge base
- tasks: things you have to do
- templates: helping you structure your notes by following common patterns.

Let's see in more detail what is the logic behind these folders.

## kb

I wanted my kb to capture the fact that notes have different levels of:
- maturity: how much time and effort has been dedicated to the note
- contribution: how much unique contribution have I personally done to the note

I then created a 3x3 matrix based on maturity x contribution.

It looks like this.

### Note Types Matrix

| Maturity ↓ \ Contribution → | Level 0 (Copied) | Level 1 (Some Input) | Level 2 (Original Work) |
| ------------------------------- | -------------------- | ------------------------ | --------------------------- |
| Level 0 (Fleeting)          | Fragment         | Thought              | Idea                    |
| Level 1 (Explored)          | Snippet          | Annotation           | Insight                 |
| Level 2 (Developed)         | Collection       | Reflection           | Masterwork              |

1. **Fragment** (Maturity 0, Contribution 0): A raw, unrefined piece of information, copied or noted without much thought.
2. **Thought** (Maturity 0, Contribution 1): A fleeting idea or personal reflection with minimal development.
3. **Idea** (Maturity 0, Contribution 2): A creative and original concept or brainstorm, still in its early stages.
4. **Snippet** (Maturity 1, Contribution 0): A slightly more explored copied excerpt with minor organization or exploration.
5. **Annotation** (Maturity 1, Contribution 1): A purposeful note combining copied material and light commentary.
6. **Insight** (Maturity 1, Contribution 2): A deeper, original exploration or conclusion.
7. **Collection** (Maturity 2, Contribution 0): A highly organized set of references, quotes, or external research material.
8. **Reflection** (Maturity 2, Contribution 1): A structured and thoughtful analysis combining external research with your own insights.
9. **Masterwork** (Maturity 2, Contribution 2): A fully developed and polished idea or creation that is highly mature and unique.

## tasks

I wanted to make a hard split between knowledge and "things to do". 

This folder is about what you have to do and it follows a simple task life-cycle.
Feel free to shape this to your own style.

- 0.inbox: things that come to your mind as things you got to do but not necessarily now
- 1.todo: things you're picking up to do for the day
- 2.in-progress: well, you're working on this stuff
- 3.done: yay you've done it!

## templates

Each one of the 9 note types has a template.

Now, some note types have more detailed templates. The "Annotation" and "Reflection" templates are great examples of that.

The reason why I created specific templates that you can use for those notes is because when you are annotating a book, you might want to focus on different things and details than when you are annotating a video for example or a podcast for that matter.

Having said that you can choose to simply follow the regular default templates for each note type.

Ah and of course, by all means, change this to shape your style!

# Let's get started!

Here's how you can start using this repo to organize your notes:

## Option 1: Fork This Repository (Recommended)
If you want to quickly get your own repository set up with this template:
1. Click the "Fork" button at the top-right of this page to create your own copy of the repo.
2. Clone your forked repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-forked-repo.git
   ```
3. Start customizing your forked repository to suit your needs.

## Option 2: Clone This Repository
Alternatively, you can clone this repository directly to your local machine:
   ```bash
   git clone https://github.com/original-username/original-repo-name.git
   ```
   Copy the `kb`, `tasks`, and `templates` folders to wherever you want to maintain your note vault.

   This is to avoid creating notes on my repo, which is just the bootstrapper for you to go create your own stuff.

# Where to go from here?

1. **Choose Your Note-Taking Tool**  
   - If you're using **Obsidian**, you can set the folder you copied as your Obsidian vault. Simply open Obsidian, go to "Open Folder as Vault," and select your folder.  
   - If you're using another editor, navigate to the folder structure and start editing the markdown files directly.

2. **Customize the Templates**  
   Tailor the templates in the `templates` folder to match your preferred style. Feel free to add, remove, or adjust fields to suit your workflow. The templates are here to guide you, but you can always make them your own.

3. **Start Adding Notes**  
   - Begin creating notes in the `kb` folder. Use the **Note Types Matrix** to decide how to classify your notes.  
   - As you work, think about the maturity and contribution of each note and file it appropriately.

4. **Track Your Tasks**  
   Use the `tasks` folder to keep track of things you need to do. The folder is set up with a simple lifecycle (`0.inbox`, `1.todo`, `2.in-progress`, `3.done`), but feel free to adapt it to your workflow.

5. **Sync with Git (Optional)**  
   If you'd like to keep your notes version-controlled, use Git to commit and push changes back to a repository that you own. 
   This is especially useful if you plan to access your notes across multiple devices.  

   ```bash
   git add .
   git commit -m "Initial setup of my note vault"
   git push origin main
   ```

6. **Explore and Evolve**  
   Over time, you'll likely find ways to tweak the structure or add new categories. Don't hesitate to adapt this system to your needs — this is your personal knowledge base, after all!