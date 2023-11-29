# AngularJS To-Do List

**A stylish and interactive To-Do List application built with AngularJS.**

## Table of Contents
1. [**Overview**](#overview)
2. [**Features**](#features)
3. [**Code Highlights**](#code-highlights)
4. [**Contributing**](#contributing)

## Overview

**This AngularJS To-Do List is a simple and intuitive application that allows users to manage their tasks efficiently. The application leverages AngularJS features to provide a seamless user experience.**

## Features

- **Adding Tasks:** Use the form to add new tasks to your to-do list. Specify the task name and select its priority from the dropdown menu (High, Medium, Low).

- **Task Priority Styling:** Tasks are visually distinguished based on their priority. High-priority tasks are highlighted in bold red, providing a clear indication.

- **Checkbox for Completion:** Each task comes with a checkbox, allowing users to mark tasks as completed. Completed tasks are visually indicated with a line-through and green font color.

- **Input Validations:** The form includes input validations to ensure that a task name is provided before adding it to the list. Duplicate task names are also prevented.

## Code Highlights

1. **Working with Simple Angular Forms:**
   - The form is created using AngularJS directives such as `ng-submit`, `ng-model`, and `ng-show`.

2. **Working with Select and Options:**
   - The task priority is selected through a dropdown menu (`<select>`), providing users with options for High, Medium, and Low priorities.

3. **Input Validations:**
   - The form includes the `required` attribute to ensure that the task input field is not empty.
   - A custom function, `isDuplicateTask`, prevents the addition of tasks with duplicate names.

4. **Using CSS Classes:**
   - Different CSS classes are applied dynamically based on task properties, such as completion status and priority, enhancing the visual appeal of the to-do list.

5. **Form Events:**
   - The `ng-submit` and `ng-change` directives are utilized to handle form submission and checkbox changes, respectively.

6. **Custom Model Update Triggers:**
   - The task priority is bound to the `taskPriority` model, which is updated when the user selects a different priority from the dropdown menu.

7. **Custom Validation:**
   - The `isDuplicateTask` function checks whether the entered task already exists in the list, preventing the addition of duplicate tasks.

## Contributing

**Developers who wish to contribute can do so by creating a pull request and saving their code on a separate branch. Your contributions are highly valued!**
