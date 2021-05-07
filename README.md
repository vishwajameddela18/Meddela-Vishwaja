  
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
                <h1>Hello</h1>
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
