## Welcome to GitHub Pages
  
<!DOCTYPE html>
<html>
  <head>
    <script src="https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    <title>Hello</title>
  </head>
  <body>
    <div id="app" />
    
    <script type="text/babel">

      class Calculator extends React.Component {
        render() {
          return (
            <div>
                <input   type="number" value="num1"/>
                <input   type="number" value="num2"/>
                <button>Add</button>
            </div>
            
          );
        }
      }

      

      ReactDOM.render(<Calculator />, document.querySelector("#app"));
     

    </script>
  </body>
</html>
You can use the [editor on GitHub](https://github.com/vishwajameddela18/vishwajameddela18.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/vishwajameddela18/vishwajameddela18.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
