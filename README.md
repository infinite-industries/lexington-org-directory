# Lexington Area Arts Organizations Directory



## To add to Weebly 

Under **Build Tab**, use *Embedded Code* widget to add the following

Under **Theme Tab**, use *CodeEditor* to append the following to the end of MyTheme -> STYLES -> main.less

```
#orglist-container {
  display: flex;
  flex-wrap: wrap;
  direction: row;
  
  font-family: sans-serif;
}

#orglist-container .org-listing {
  width: 400px;
  border: 1px grey solid;
  border-radius: 5px;
  padding: 25px;
  margin: 10px;
  
  text-align: left;
  background-color: white;
  
}

#orglist-container #credits {
  width: 400px;
  border: 1px grey solid;
  background: lightgrey;
  border-radius: 5px;
  padding: 25px;
  margin: 10px;
  
}

#orglist-container #credits .links-to-orgs {
  margin-top: 45px;
}

#orglist-container ul {
  list-style-type: none;
  padding: 0px;
}

#orglist-container .mission {
  font-family: serif;
  color: black;
}

#orglist-container .title {
  font-size: 1.2em;
  color: black;
}

#orglist-container .title-container {
  margin-bottom: 20px;
  color: black;
}

#orglist-container .website-container {
  overflow: hidden;
  max-width: fit-content;
  color: black;
}
```

Updated 05/11/2021
