# GULP PROJECT 

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


This is a personal project for creating a task runner for converting SCSS to CSS and minifying CSS, Images, and JS.

### :scroll: Gulp Commands

|GULP NAME | DESCRIPTION  |
|----|----|
|  build  |  minifies the CSS, Images, JS and sends it to the **public** folder |
| rebuild  | deletes existing **public** folder and creates newer one  |
| watch | watches every file save on **src** folder then modify it |
| clean  | Removes files and folders |


### :computer: Usage

If you want to make an static html you can remove the folders [controller, model, views, model] on the **src/** and on the root you can remove the **index.js**, since I did express, ejs in this project.

##### Code Block
    npm install
    gulp build && gulp watch

### :heavy_heart_exclamation: Acknoledgements and References

- This Project uses [FLOCSS](https://github.com/hiloki/flocss/blob/master/README_eng.md) for the CSS architecture methodology