# Instagram Landing Page Homework

## Summary

The task for this homework was to recreate the signup page from [Instragram](https://www.instagram.com) and make it responsive.

## Features

* A signup form, with buttons
* Image of phone placed side by side with signup form
* Image and form retain their position regardless of page size
* Link to 'Log In'
* App images underneath form
* Footer with links and copyright

![Full Page Layout](images/Screenshot_1.png)

## Responsive Design

The second part of the task was to hide the phone image when the page reduces to mobile size.

In CSS I used a `@media` query to change the styling of the page wen the width became a certain size.

```
@media (max-width: 962px){
  .PhoneImg {
    display: none;
  }
```

When the image is hidden I also expanded the width of the form to fill the screen.

```
.SignUpForm {
  width:100%;
  display: block;
}
```
![Mobile Layout](images/Screenshot_2.png)
