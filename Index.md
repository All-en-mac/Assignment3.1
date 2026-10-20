Step 1: index.html (Home Page)
Create your index.html file and paste the following code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home — My Website</title>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.html">Home</a> | 
        <a href="about.html">About</a> | 
        <a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a>
    </nav>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Main Content -->
    <main>
        <section>
            <h2>Home Page Introduction</h2>
            <p>Hello! Welcome to the home page of my simple two-page website. You can use the navigation bar above to switch between pages or explore external web development resources securely in a new tab.</p>
        </section>
    </main>

</body>
</html>
Step 2: about.html (About Page)
Create your about.html file in the same folder and paste the following code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About — My Website</title>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.html">Home</a> | 
        <a href="about.html">About</a> | 
        <a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a>
    </nav>

    <!-- Header Section -->
    <header>
        <h1>About This Project</h1>
    </header>

    <!-- Main Content -->
    <main>
        <section>
            <h2>Background & Details</h2>
            <p>This page provides more background information about this project. It is built as part of the web development practice curriculum to master internal routing, relative paths, external linking, and security best practices.</p>
        </section>
    </main>

</body>
</html>
How Requirements Were Satisfied
Two Files: Created index.html and about.html in the project directory.

Navigation Bar: Included top navigation links on both pages to move seamlessly between views.

Internal Linking: Connected the pages using relative anchor links (href="index.html" and href="about.html").

External Link with Security: Linked out to MDN Web Docs using target="_blank" to open in a new tab and rel="noopener noreferrer" to protect against potential security vulnerabilities.

Submission Checklist
Save both index.html and about.html inside your project directory.

Test the links locally using Live Server to verify that clicking "About" opens about.html, clicking "Home" brings you back, and clicking the external link opens in a separate secure tab.

Submit both HTML files and a screenshot of your browser rendering the navigation bar and home page!