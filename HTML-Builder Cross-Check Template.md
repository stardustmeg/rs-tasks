## 01-read-file

- [ ] **01-read-file (if all points below are successfully checked: +20 points)**

  - [ ] Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.
        If synchronous methods or a timer are used, the task is considered not completed - 0 points.

  - [ ] Make sure that a ReadStream is used to read the file.
        If a stream is not used for reading the file, the task is considered not completed - 0 points.

  - [ ] In the root directory of the repository, execute the command `node 01-read-file` and make sure that the contents of the text.txt file are output to the console (the presence/absence of empty lines at the end of the file is not checked).
        In case of errors or empty output when there is text in `text.txt`, the task is considered not completed - 0 points.

  - [ ] Change the contents of the `text.txt` file and run the command `node 01-read-file` again. The result should correspond to the current state of `text.txt`, otherwise, the task is considered not completed - 0 points.

## 02-write-file

- [ ] **02-write-file (if all points below are successfully checked: +20 points)**

  - [ ] Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.
        If synchronous methods or a timer are used, the task is considered not completed - 0 points.

  Make sure that there is only one file named `index.js` in the `02-write-file folder`. If not, remove all unnecessary files from the task folder.

  - [ ] In the root directory of the repository, execute the command `node 02-write-file` and ensure that a prompt for entering text appears in the console, and a text file has been created in the `02-write-file` directory.
        In case of errors or instant completion of the task execution, it is considered not completed - 0 points.

  - [ ] After entering the text, make sure that the input is correctly recorded in the created text file.
        If this does not happen or the process ends without expecting further input, the task is considered not completed - 0 points.

  - [ ] Use the `ctrl/cmd + c` key combination. A farewell phrase should be displayed in the console with subsequent process termination.
        If the process does not end or a farewell phrase is not displayed, -10 points.

  - [ ] Run the script and enter `exit`. A farewell phrase should be displayed in the console with subsequent process termination.
        If the process does not end or a farewell phrase is not displayed, -10 points.

## 03-files-in-folder

- [ ] **03-files-in-folder (if all points below are successfully checked: +20 points)**

  - [ ] Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.
        If synchronous methods or a timer are used, the task is considered not completed - 0 points.

  - [ ] In the root directory of the repository, execute the command `node 03-files-in-folder`. Information about files inside the secret-folder should be displayed in the console (information about files in subfolders should not be displayed).
        If you encounter an error during execution or receive incorrect information about files, the task is considered not completed - 0 points.

  Add one or more files of different sizes to the `secret-folder`.

  Add two folders to the `secret-folder`. In the name of one of the folders, specify a fake extension (e.g., `my-folder.js`).

  - [ ] Run the script with the command `node 03-files-in-folder` and check the correctness of the displayed data.
        If the information about added files is incorrect or if data about directories is displayed, the task is considered not completed - 0 points.

## 04-copy-directory

- [ ] **04-copy-directory (if all points below are successfully checked: +20 points)**

  - [ ] Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.
        If synchronous methods or a timer are used, the task is considered not completed - 0 points.

  - [ ] Check the `index.js` file for the presence of the experimental function **fsPromises.cp()**.
        If this function is used, the task is considered not completed - 0 points.

  Open the files folder and make sure it is not empty. Otherwise, create several files at your discretion.

  In the root directory of the repository, execute the command `node 04-copy-directory`.

  - [ ] After the script execution is complete, check the `04-copy-directory` folder for the presence of the created files-copy folder with an exact copy of the content of the original files folder.
        If this folder is missing or its content does not match the content of the files folder, the task is considered not completed - 0 points.

  Add several new files to the files folder and delete one of the previously existing ones. Run the command `node 04-copy-directory`.

  - [ ] Ensure that the content of the `files-copy` folder is updated and corresponds to the content of the files folder.
        If an error occurred during execution or the state of the `files-copy` folder was not updated, the task is considered not completed - 0 points.

## 05-merge-styles

- [ ] **05-merge-styles (if all points below are successfully checked: +20 points)**

  - [ ] Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.
        If synchronous methods or a timer are used, the task is considered not completed - 0 points.

  Ensure that only the `index.html` file is present in the `project-dist` folder. If there are any extraneous files, delete them.

  - [ ] In the root directory of the repository, execute the command `node 05-merge-styles`. For a better understanding of the script's operation, you can open the `index.html` file using the Live Server extension.
        If there are errors during the script's execution, the task is considered not completed - 0 points.

  - [ ] Check the content of the `bundle.css` file. The content of the file and the styling format in it should match the source files, and styles should not be merged. The sequence of styles is not checked!
        If `bundle.css` contains incorrect styles, the task is considered not completed - 0 points.

  Change the content of the `styles` folder by removing one or more style files, or replace the `styles` folder and `project-dist/index.html` with the content of the `test-files` folder (the previously generated `bundle.css` file should remain in `project-dist`).

  In the `styles` folder, add a file with an extension other than css and content like `ext-test-string` (or any other string of your choice).

  - [ ] Run the script and ensure that the `bundle.css` file is overwritten and contains up-to-date and correct styles.
        If this does not happen, the task is considered not completed - 0 points.

  - [ ] Search for the string `ext-test-string` (or the string written in a file with an extension other than css) in the `bundle.css` file using the `ctrl/cmd + f` key combination.
        If the string is present in the file, the task is considered not completed - 0 points.

## 06-build-page

- [ ] **06-build-page (if all points below are successfully checked: +50 points)**

  - [ ] Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.
        If synchronous methods or a timer are used, the task is considered not completed - 0 points.

  - [ ] Check the `index.js` file for the presence of the experimental function **fsPromises.cp()**.
        If this function is used, the task is considered not completed - 0 points.

  In the root directory of the repository, execute the command `node 06-build-page`.

  - [ ] After the script terminates its execution, a `project-dist` folder should be created in the `06-build-page` directory, containing the `index.html` and `style.css` files, as well as the assets folder.
        If this does not happen, the task is considered not completed - 0 points.

  - [ ] Ensure that the `index.html` file contains markup from the `template.html` file with the replacement of template tags with the markup of similarly named component files from the components folder. The markup of component files should be strictly in the places corresponding to the template tags. There should be no template tags themselves in the `index.html` file.
        If this is not the case, the task is considered not completed - 0 points.

  - [ ] Check the `style.css` file for the correct assembly of styles from the `styles` folder. Similar to the task `05-merge-styles`, styles should maintain formatting and not interfere with each other.
        If the styles are assembled incorrectly, the task is considered not completed - 0 points.

  Note that when using liveServer, you may notice minor styling issues in the `footer`. This case is not considered an error.

  - [ ] Open the `assets` folder. Ensure that its content and the content of subfolders inside it exactly match the content of the assets folder in `06-build-page/assets`.
        If this is not the case, the task is considered not completed - 0 points.

  Add the test files from the `test-files` folder to the project:

  `06-build-page/test-files/components/about.html` -> `06-build-page/components/about.html`

  `06-build-page/test-files/images/squirrel-2.jpg` -> `06-build-page/assets/img/squirrel-2.jpg`

  `06-build-page/test-files/styles/about.css` -> `06-build-page/styles/about.css`
  Don't forget to specify the new template tag (`{{about}}`) in the `template.html` file. Then, repeat steps 3-7.
