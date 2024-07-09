# 10kCoders_Absolute-relativepath

It is a Static Web Page created Using  Absolute and relative paths in HTML




**Absolute Paths**
An absolute path specifies the complete URL to a resource. This means it includes the protocol (such as http:// or https://), the domain name, and the full path to the resource.

**Advantages of Absolute Paths:**
Consistency: The resource will be fetched from the exact same location, no matter where the HTML document is.
External Resources: Useful for linking to resources hosted on different servers.

**Disadvantages of Absolute Paths:**
Dependency on Domain: If the domain changes, all absolute paths need to be updated.
Longer URLs: Absolute paths are usually longer and can make the code harder to read.

**Relative Paths**
A relative path specifies the location of a resource in relation to the current document. Relative paths are shorter and more flexible than absolute paths.
Types of Relative Paths:
Same Directory,
This refers to an image located in the same directory as the HTML file.
Subdirectory:
This refers to an image located in the images subdirectory of the current directory.
Parent Directory:
The .. indicates moving up one level to the parent directory.
Root Directory:
The leading / refers to the root directory of the website
 
**Advantages of Relative Paths:**
Flexibility: Easier to move entire directories or projects without changing paths.
Shorter URLs: More concise and easier to manage.
**Disadvantages of Relative Paths:**
Context Dependent: Paths can break if the directory structure changes.
Less Clear: Can be harder to understand where the resource is located, especially in deeply nested directories.
 

