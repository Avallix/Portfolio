# Welcome to MkDocs 101, Uncle Moe!

Hello Uncle Moe! Austin has set up this guide especially for you to introduce you to the wonders of MkDocs. By the end of this guide, you'll have a basic understanding of setting up MkDocs and hosting the documentation on GitHub.

## What is MkDocs?

MkDocs is a fast, simple, and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

### Static vs. Dynamic Sites:

- **Static Sites**: These are pre-rendered HTML files. They're fast, secure, and can be easily hosted on platforms like GitHub Pages. MkDocs generates static sites.
  
- **Dynamic Sites**: Unlike static sites, dynamic sites generate content in real-time. Think of platforms like WordPress. They can be more flexible but also require more resources.

## Setting Up MkDocs:

1. **Installation**:
   - Install MkDocs with Python by running: `pip install mkdocs`
   
2. **Start a New Project**:
   - Create a new directory for your project: `mkdocs new [dir-name]`

3. **Serve the Project Locally**:
   - Navigate to your project directory and run: `mkdocs serve`
   - This will start a local server. You can view your documentation by opening a web browser and navigating to `http://127.0.0.1:8000/`.

4. **Build the Documentation**:
   - Once you're ready, build the static files by running: `mkdocs build`

## Hosting on GitHub:

Once you've set up and built your documentation, you can host it on GitHub Pages. 

1. Push your MkDocs project to a GitHub repository.
2. Build the static site with: `mkdocs build`
3. Deploy it to GitHub Pages with: `mkdocs gh-deploy`
4. Your site will then be accessible at `https://[username].github.io/[repository-name]/`.

Remember, each time you make updates to your documentation, run `mkdocs gh-deploy` to see those changes online.

## Dive Deeper:

- `mkdocs -h`: To see a list of all available commands and their purpose.
- Explore themes, plugins, and extensions to enhance your documentation's appearance and functionality.

---

I hope this guide provides a clear introduction to MkDocs and its capabilities, Uncle Moe. Feel free to reach out if you have any questions or need further clarifications. Enjoy documenting!


##[Linking](links.md)
[Links](links.md)