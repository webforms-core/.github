# WebForms Core Technology

WebForms Core is an advanced technology for manipulating HTML tags on the server. It is a radical technology that eliminates the need for front-end development. Using WebForms Core is the easiest way to build web-based systems.

### Example

**Server code**
```csharp
WebForms form = new WebForms();

form.AddTag("<form>", "h3");
form.AddText("<h3>-1", "File was upload.");
form.AddTag("<form>", "img");
form.SetAttribute("<form>|<img>-1", "src", FilePath);
form.SetWidth("<form>|<img>-1", 400);

Write(form.Response());
```

Result
-
![WebForms Core Technology - Image Upload Example](https://github.com/user-attachments/assets/57dc4b66-e051-4157-b162-515a1438aac7)
-
