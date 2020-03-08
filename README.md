## Basic File Upload

**Your HTML file upload form:**
```html
<html>
  <body>
    <form ref='uploadForm' 
      id='uploadForm' 
      action='http://localhost:8000/upload' 
      method='post' 
      encType="multipart/form-data">
        <input type="file" name="sampleFile" />
        <input type='submit' value='Upload!' />
    </form>     
  </body>
</html>
```

