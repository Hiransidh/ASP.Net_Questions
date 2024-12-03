# Web Forms Development - Questions

## One-Word Questions

1. What is the default extension of a Web Form? **`.aspx`**  
2. Which property is used to check if the page is loaded for the first time? **`IsPostBack`**  
3. What control is used to group related content in a collapsible section? **`Panel`**  
4. What server control allows uploading files to the server? **`FileUpload`**  
5. What property is used to store and retrieve data across postbacks? **`ViewState`**  
6. What is the default method used by forms in Web Forms? **`POST`**  
7. Which class is the parent of all Web Form controls? **`System.Web.UI.Control`**  
8. What control allows creating master-detail relationships? **`GridView`**  
9. What property of a Button control specifies its action when clicked? **`CommandName`**  
10. What method permanently redirects the user to another page? **`Response.Redirect`**  
11. Which lifecycle event occurs just before the rendering of a page? **`PreRender`**  
12. Which server-side control is used to validate user input? **`RequiredFieldValidator`**  
13. What type of event is triggered when a DropDownList selection changes? **`SelectedIndexChanged`**  
14. Which object stores query string values sent by the client? **`Request.QueryString`**  
15. What property sets the background color of a control? **`BackColor`**  
16. Which control is used for creating forms with multiple steps? **`Wizard`**  
17. What event occurs after all controls on a page have been initialized? **`InitComplete`**  
18. Which control is used for displaying tabular data? **`GridView`**  
19. Which ASP.NET control allows dynamic addition of child controls? **`PlaceHolder`**  
20. What is the name of the configuration file for ASP.NET applications? **`Web.config`**

---

## MCQs

### Page Life Cycle

1. **What is the first event triggered in the page lifecycle?**  
   - a) Load  
   - b) PreRender  
   - c) Init  
   - d) Render  
   **Correct: c**

2. **Which event occurs only once during the lifecycle of a page?**  
   - a) Load  
   - b) Init  
   - c) PreRender  
   - d) Unload  
   **Correct: b**

3. **Which lifecycle event is triggered after all child controls have been initialized?**  
   - a) Load  
   - b) InitComplete  
   - c) PreLoad  
   - d) Render  
   **Correct: b**

---

### Web Controls

4. **Which control is used to create a drop-down menu?**  
   - a) ComboBox  
   - b) DropDownList  
   - c) ListBox  
   - d) RadioButtonList  
   **Correct: b**

5. **Which control allows uploading a file in ASP.NET?**  
   - a) FileSelector  
   - b) FileUpload  
   - c) FileControl  
   - d) FilePicker  
   **Correct: b**

6. **Which control is used to navigate between pages?**  
   - a) Button  
   - b) HyperLink  
   - c) LinkButton  
   - d) NavigationButton  
   **Correct: b**

---

### Validation

7. **Which control is used to validate a user's email address?**  
   - a) CustomValidator  
   - b) RangeValidator  
   - c) RegularExpressionValidator  
   - d) CompareValidator  
   **Correct: c**

8. **What happens if a validation control fails?**  
   - a) Page submission continues  
   - b) Page submission stops  
   - c) Error is logged  
   - d) Nothing happens  
   **Correct: b**

9. **Which property of a validation control displays the error message?**  
   - a) Text  
   - b) Message  
   - c) ErrorText  
   - d) Value  
   **Correct: a**

---

### View State

10. **Which property is used to enable or disable ViewState for a control?**  
    - a) EnableState  
    - b) EnableViewState  
    - c) StateEnabled  
    - d) ViewStateEnabled  
    **Correct: b**

11. **What is stored in ViewState?**  
    - a) Server-side data  
    - b) Client-side data  
    - c) Cookies  
    - d) Session data  
    **Correct: b**

---

### Master Pages

12. **What is the extension of a Master Page?**  
    - a) .aspx  
    - b) .asmx  
    - c) .master  
    - d) .config  
    **Correct: c**

13. **How do you bind a content page to a master page?**  
    - a) Use the `Content` tag  
    - b) Set `MasterPageFile` attribute  
    - c) Include the master file  
    - d) Call the master file explicitly  
    **Correct: b**

---

### Data Binding

14. **Which control is primarily used for displaying data in a grid format?**  
    - a) GridView  
    - b) DataList  
    - c) Repeater  
    - d) ListView  
    **Correct: a**

15. **Which event is triggered before a GridView row is rendered?**  
    - a) RowUpdating  
    - b) RowDataBound  
    - c) RowDeleting  
    - d) RowEditing  
    **Correct: b**

16. **Which method is used to bind data to a DataGrid control?**  
    - a) Bind()  
    - b) DataBind()  
    - c) Render()  
    - d) DataControl()  
    **Correct: b**

---

### Navigation

17. **Which control is used for creating menus in Web Forms?**  
    - a) Menu  
    - b) NavigationBar  
    - c) SiteMapPath  
    - d) TreeView  
    **Correct: a**

18. **Which navigation control displays the hierarchical structure of a website?**  
    - a) TreeView  
    - b) Menu  
    - c) SiteMapPath  
    - d) GridView  
    **Correct: a**

---

### Query String

19. **Which object is used to retrieve query string values?**  
    - a) Request.QueryString  
    - b) Response.QueryString  
    - c) Session.QueryString  
    - d) ViewState.QueryString  
    **Correct: a**

20. **Which property in the URL is used to pass data using a query string?**  
    - a) #  
    - b) &  
    - c) ?  
    - d) /  
    **Correct: c**

---

### Miscellaneous

21. **Which directive is used at the beginning of an ASP.NET page?**  
    - a) @Include  
    - b) @Page  
    - c) @Control  
    - d) @Namespace  
    **Correct: b**

22. **What file contains the application’s configuration settings?**  
    - a) App.config  
    - b) Web.config  
    - c) Global.asax  
    - d) Settings.json  
    **Correct: b**

23. **What is the default method for form submission in Web Forms?**  
    - a) GET  
    - b) POST  
    - c) PUT  
    - d) DELETE  
    **Correct: b**
