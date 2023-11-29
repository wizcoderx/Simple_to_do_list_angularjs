# AngularJS To-Do List with Typing Animation

**A stylish and interactive To-Do List application built with AngularJS, featuring a unique typing animation.**

## Table of Contents
1. [**Overview**](#overview)
2. [**Code Highlights**](#code-highlights)
3. [**Styling Details**](#styling-details)
4. [**Contributing**](#contributing)

## Overview

**This AngularJS To-Do List is not just functional but also visually engaging with a creative typing animation. Manage your tasks efficiently while enjoying a dynamic user experience.**

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

6. **Custom Validation:**
   - The `isDuplicateTask` function checks whether the entered task already exists in the list, preventing the addition of duplicate tasks.

## Styling Details

- The page features a stylish and eye-catching typing animation for the header "To-Do List..."
- The background is set to black, providing a sleek and modern appearance.
- High-priority tasks are highlighted in bold red, and completed tasks have a line-through and green font color.

## Contributing

**Developers who wish to contribute can do so by creating a pull request and saving their code on a separate branch. Your contributions are highly valued!**
