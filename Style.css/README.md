/* ======= Base Styles ======= */

body {
  font-family: Arial, sans-serif; /* Set default font */
  margin: 0;                     /* Remove default browser margin */
  padding: 0;                    /* Remove default browser padding */
  background-color: black;      /* Set background color for the entire page */
  color: white;                 /* Set default text color */
}

/* ======= Header & Navigation ======= */

header {
  background-color: grey;       /* Set header background color */
  padding: 30px 0;              /* Top and bottom padding */
}

.logo-nav {
  display: flex;                /* Use flexbox layout */
  align-items: center;         /* Vertically align items */
  justify-content: space-between; /* Space between logo and nav links */
  padding: 0 30px;              /* Side padding */
}

.logo {
  height: 50px;                 /* Set logo height */
  width: auto;                  /* Keep aspect ratio */
}

nav ul {
  display: flex;                /* Arrange nav items horizontally */
  justify-content: flex-end;   /* Align items to the right */
  list-style: none;            /* Remove default bullet points */
  padding: 0;
  margin: 0;
}

nav ul li {
  margin: 0 15px;               /* Horizontal spacing between links */
}

nav ul li a {
  color: black;                 /* Link color */
  text-decoration: none;       /* Remove underline */
  font-weight: bold;           /* Bold text */
  transition: color 0.3s ease, background-color 0.3s ease; /* Smooth hover effect */
}

nav ul li a:hover {
  color: white;                 /* Text turns white on hover */
  background-color: black;     /* Background turns black on hover */
  padding: 5px 10px;           /* Add padding for hover effect */
  border-radius: 5px;          /* Rounded corners on hover */
}

/* ======= Section Layout ======= */

section {
  padding: 30px;                /* Inner spacing */
  max-width: 100%;              /* Allow full width */
  margin: 0;
}

/* ======= Section Styles ======= */

.section-light {
  background-color: white;     /* Light background */
  color: black;                /* Dark text */
}

.section-light h1,
.section-light h2 {
  color: black;                /* Override heading color in light section */
}

.section-dark {
  background-color: grey;      /* Darker background */
  color: white;                /* Light text */
}

/* ======= Headings ======= */

h1, h2 {
  text-align: center;          /* Center headings */
  color: white;                /* Default heading color */
}

/* ======= List Styles ======= */

ul {
  list-style-type: square;     /* Square bullets */
  padding-left: 20px;          /* Indentation */
}

/* ======= Project Section ======= */

.project {
  margin: 20px 0;              /* Vertical spacing */
  padding: 15px;               /* Inner spacing */
  border: 1px solid #ccc;      /* Light gray border */
  background-color: #fff;      /* White background */
}

/* ======= Form Styles (Contact) ======= */

form {
  display: flex;               /* Flex layout for form */
  flex-direction: column;      /* Stack inputs vertically */
}

form input, form textarea, form button {
  margin: 10px 0;              /* Vertical spacing between elements */
  padding: 10px;               /* Inner padding */
  font-size: 16px;             /* Readable font size */
}

/* ======= Footer ======= */

footer {
  text-align: center;          /* Center text */
  padding: 20px;               /* Inner spacing */
  background-color: grey;      /* Background color */
  color: white;                /* Text color */
}

footer .social-links {
  list-style: none;            /* Remove bullets */
  padding: 0;
  margin-top: 10px;
  display: flex;               /* Horizontal layout */
  justify-content: center;     /* Center links */
  gap: 20px;                   /* Space between links */
}

footer .social-links a {
  color: white;                /* White link text */
  text-decoration: none;       /* No underline */
  font-weight: bold;           /* Bold text */
}

footer .social-links a:hover {
  text-decoration: underline;  /* Underline on hover */
}
