### **Lesson 02: Image Layouts and picture Tag **

#### **Objective:**

In this lesson, students will refine the media gallery by adding a new responsive image using the `<picture>` tag.

NOTE: The file names are just examples. You will need to update the code based on the files you find online.

---

### **Step-by-Step Guide**

#### **Step 1: Add Responsive Image Using the `<picture>` Tag**

1. In the next row of the existing table, add a responsive image using the `<picture>` tag. Find your own photos from online. Make sure to save the all three images inside the images folder:
   ```html
   <tr>
     <td colspan="3">
       <picture>
         <source media="(max-width: 600px)" srcset="small-image.jpg" />
         <source media="(max-width: 1200px)" srcset="medium-image.jpg" />
         <img
           src="large-image.jpg"
           alt="Description of Responsive Image"
           title="This is a responsive image"
           width="150"
           height="100"
         />
       </picture>
     </td>
   </tr>
   ```

#### **Step 2: Save and Preview Your Form**

2. Save your index.html file.
3. Open it in a web browser to preview your media gallery.

#### **Step 3: Submit Your Work:**

4. Once you've confirmed that the media gallery looks good, submit the following:
   - The zipped media-gallery folder with the index.html file and images folder that contains 6 images.
   - Upload it to the classwork assignment on Google Classroom

#### **Assessment Criteria:**

- **Table Layout:** Organizes images and captions using a table with appropriate rows and columns.
- **Responsive Image:** Successfully adds a new image using the <picture> tag, demonstrating responsive design.
