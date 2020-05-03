# How to Test JavaScript JSON Code
If you have your file structure as shown below:  
- Parent Folder
    - HTML File
    - JSON File

Then navigate to the Parent Folder in your File Explorer and within your **terminal**, run:  
```python
#Replace local_num with some number (I used 1337)
python -m http.server [local_num]
```
This is a test edit to see how this goes.  This is another test line to make sure that this is adding properly.  
Then, in your browser, go to http://localhost:1337/index.html, where you can replace the *1337* portion of the URL with your *local_num* that you selected earlier.  

**This is the *only* way for you to be able to see the JavaScript Code successfully load the JSON Data**
