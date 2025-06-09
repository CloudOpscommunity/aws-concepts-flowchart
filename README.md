AWS Roadmap Website
This is a static website showcasing an AWS Learning Roadmap flowchart, built with HTML and CSS. It features animated dotted arrows for interactivity and is optimized for hosting on GitHub Pages.


File Structure
aws-roadmap/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # CSS styles for the flowchart
└── README.md           # Project documentation

Setup for GitHub Pages

Create a Repository:

Create a new repository on GitHub (e.g., aws-roadmap).
Alternatively, use username.github.io for a personal site.


Upload Files:

Clone the repository: git clone https://github.com/username/aws-roadmap.git
Copy the index.html, css/styles.css, and README.md files into the repository, maintaining the folder structure.
Commit and push: git add . && git commit -m "Initial commit" && git push origin main


Enable GitHub Pages:

Go to your repository’s Settings > Pages.
Set the source to the main branch and / (root) folder.
Save, and access the site at https://username.github.io/aws-roadmap.



Customization

Flowchart Content: Edit the .box and .sub-box elements in index.html to adjust services or steps.
Styling: Modify css/styles.css for colors, sizes, or animation speed.
Assets: Add images to the assets/ folder and reference them in index.html if needed.

Technologies

HTML5
CSS3 (with animations)
Hosted on GitHub Pages

Notes

The animated dotted arrows use CSS linear-gradient for a lightweight effect.
The site is responsive and accessible, with ARIA labels and high-contrast colors.
AWS branding colors are used (#ff9900 for orange, #232f3e for navy).

