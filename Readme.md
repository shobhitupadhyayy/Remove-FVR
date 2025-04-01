
# Remove Invalid Field Visibility Rules

This script removes the Invalid Field Visibility Rules from the content type schema and updates in the schema.json file.


## How to run 

* **Clone the project**

```bash
git clone https://github.com/contentstack-expert-services/CommerceTool-POC.git
```
* **Install the dependencies**

```bash
  cd my-project
  npm install
```
* **Enter the path of your exported data**

```bash
1) Go to the index.js file in your project and enter the file path for the const variable

    const filePath = 'Specify your local file path here till schema.json';
    example - const filePath = 'Users/xyz/exportedData/content_types/schema.json'

```

* **Run index.js**

```bash
  node index.js
```

**Once the script is completed running it will generate a log report of all the content types which are updated and removed the invalid FVR** 