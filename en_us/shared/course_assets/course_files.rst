.. _Add Files to a Course:

###########################
Adding Files to a Course
###########################

Adding files, such as images, that you can use in your course has the following
steps.

.. image:: ../../../shared/images/AddFiles.png
 :alt: A workflow diagram showing the steps to add and show a file in a course
     or on the internet.

#. The course team uploads the files on the **Files & Uploads** page in Studio.
#. Studio generates URLs for the files.
#. The course team adds a link to the file's URL in the course content, such as
   inside a component, or in an email or external web page.
#. The file is visible in the course, email, or external web page.

For more information, see the following topics.

.. contents::
  :local:
  :depth: 1

.. _The Files and Uploads Page:

*************************
The Files & Uploads Page
*************************

You manage most files for your course, including image files, on the **Files &
Uploads** page. This page lists the files that you upload, along with the
following information about the files.

* The file name.
* A preview of the file (if the file is an image).
* The file type.
* The date the file was added.
* The URLs that you use to make your files visible in your course or on the
  internet.
* An indication of whether the file is :ref:`locked<Lock a File>`.

.. note::
  For textbooks or for course handouts that you want to make available in the
  sidebar of the **Course** page, see :ref:`Adding Textbooks` or :ref:`Add
  Course Handouts`.

.. _File Size:

*******************
File Size
*******************

You can upload more than one file at a time. The maximum combined file size for
an upload is 10 MB. We recommend that you use standard compression tools to
reduce PDF and image file sizes before you add the files to your course.

If you have very large audio files or large data sets to share with your
students, do not use the **Files & Uploads** page to add these files to your
course. Instead, use another hosting service to host these files.

.. _Upload a File:

*******************
Upload a File
*******************

.. note::
  Ensure that you obtain copyright permissions for files and images you upload
  to your course, and that you cite sources appropriately.

To upload a file, follow these steps.

#. Create or locate the file on your computer.

   .. note::
     When Studio generates URLs for uploaded files, the file name becomes part
     of the URL and is visible to students when they access the file. Avoid
     using file names that contain information that you do not want to share
     about the file contents, such as "Answerkey.pdf".

#. On the **Content** menu, select **Files & Uploads**.

#. On the **Files & Uploads** page, drag your file into the **Drag and Drop**
   area.

   .. note::
     If you upload a file that has the same name as an existing course file,
     the original file is overwritten without warning.

The **Files & Uploads** page refreshes to show the uploaded file.

To upload additional files, drag more files into the **Drag and Drop** area of
the page.

.. _File URLs:

*************************************************
Use an Uploaded File Inside or Outside the Course
*************************************************

When you upload a file, Studio assigns a Studio URL and a web URL to the file.
The **Copy URLs** column on the **Files & Uploads** page lists these URLs. To
use an uploaded file, you add a link to the Studio URL or the web URL in your
content.

.. note::
  If you do not want to allow access to a file from outside your course, you
  can lock the file so that only learners who are signed in and enrolled in
  your course can access the file. For more information, see :ref:`Lock a
  File`.

* To add a file or image to a component, a course update, or a course handout,
  use the Studio URL.

  For more information, see :ref:`Add an Image to an HTML Component`.

* To provide a link to the file or image from outside the course, including in
  a bulk email message that you send from the LMS, use the web URL.

  Be sure that you do not use the Studio URL in an email message. For more
  information about sending email messages, see
  :ref:`Send_Bulk_Email`.

To copy a URL from the file list, select the **Studio** or **Web** option in
the **Copy URLs** column. The **Studio** or **Web** option briefly changes to
"Copied" when the operation is complete.

.. _Sort Files:

*********************
Sort Files
*********************

On the **Files & Uploads** page, you can sort your files by name, type, or date
added. To sort by one of these columns, select the name of the column. For
example, to sort your files by type, select the **Type** column name.

The arrow or arrows to the right of the column name indicate the column sort
order. Files are sorted by the column that has one arrow. The direction of the
arrow indicates whether the order is ascending or descending.

To change between ascending and descending order, select the column name again.

.. _Filter Files:

*********************
Filter Files
*********************

You can filter the list of files by type so that only a selected type of file
is visible. The list remains in the current sort order.

You can filter by the following file types.

.. list-table::
   :header-rows: 1
   :widths: 10 20

   * - Type
     - Possible File Name Extensions
   * - Audio
     - .aac, .mpeg, .mp3, .ogg, .wav
   * - Code
     - .css, .html, .json, .php, .sql
   * - Documents
     - .pdf, .txt, Microsoft Office and Open Office documents, presentations,
       spreadsheets
   * - Images
     - .gif, .ico, .jpg, .jpeg, .png, .tif, .tiff
   * - Other
     - Files not included in the other types, such .sjson

To filter the list of files by type, follow these steps.

#. On the **Files & Uploads** page, locate **Filter by File Type**.
#. In the list, select the checkboxes for the types of file that you want.

The list refreshes to show only the type or types of file you selected. You can
sort the resulting list by name, type, and date added.

To reset the list and view files of all types, clear all checkboxes.

.. _Find Files:

*******************
Find a File
*******************

The **Files & Uploads** page lists up to 50 files at one time.  If your course
has more than 50 files, additional files are listed on other pages.

You can navigate through the pages in the following ways.

* Select **Previous** or **Next** to navigate to the previous or next page.
* Select the number of the page that you want to view.

.. _Lock a File:

*******************
Lock a File
*******************

By default, anyone can access a file you upload if they know the web URL, even
if they are not enrolled in your course. You can prevent outside access to a
file by locking the file. When you lock a file, the web URL only allows
learners who are enrolled in your course and signed in to access the file.

To lock a file, select the lock icon in the row for the file.

.. _Delete a File:

*******************
Delete a File
*******************

To delete a file, select the delete icon in the row for file, and then select
**Permanently delete** in the confirmation dialog box.

.. warning::
  After you delete a file, any links to the file from inside or outside the
  course will be broken. You must update links to files that you need to
  delete.
