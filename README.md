# Co-op Front-end Technical Test

This test is designed to help us understand how you would tackle common front-end problems in an accessible and tested way.

We've been asked to update our donation component. We have a new design and functionality

We would like you to update our charity donation component. The new design is within this project for you to use as a reference.

We will focus on two goals for this test.

## Goals

### Add the new elements and update the visual design.

We are looking for how you would approach writing the HTML of the component. The focus here is on the semantics and accessibility of the markup for the new and existing code.

We also want to see how you would style the component so it matches the design and works across multiple browsers and devices. It is also useful for us to see how you would style it into a wider system of components and patterns.

### Make the component dynamic by consuming the donation data from the API and passing it to the component.

How would you approach the JavaScript that will fetch the data, tranform it and update the DOM. We're looking for clean and tested JavaScript. Tests are written using Jest.

## Mock Donation API

We have created a small API which returns some mock data for the raised and target amounts. If you can, make use of it to display dynamic data. The API endpoint itself is at https://coop-mock-test-api.herokuapp.com.

An example of the return value

```
{
  "status": "OK",
  "target": 6000,
  "raised": 3249.03
}
```
