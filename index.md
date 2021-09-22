## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Monica0013/Programming-porfolio/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown


function setup() {
    createCanvas(800, 800)
    colorMode(HSB, height, height, height);
    noStroke();
    background('white');
}

const barWidth = 100;
let lastBar = -10;

function draw() {

    let whichBar = mouseX / barWidth;
    if (whichBar !== lastBar) {
        let barX = whichBar * barWidth;
        fill(mouseY, height, height);
        rect(barX, 0, barWidth, height);
        lastBar = whichBar;
    }
    


    fill('white')
    circle(50, 50, 40, 50);

    fill(100)
    triangle(1, 150, 360, 360, 1, 360);

    fill('maroon')
    triangle(150, 150, 360, 360, 1, 360);

    fill('white')
    if (mouseIsPressed) {
        ellipse(mouseX, mouseY, 50)
    }
}


# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

[GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Monica0013/Programming-porfolio/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
