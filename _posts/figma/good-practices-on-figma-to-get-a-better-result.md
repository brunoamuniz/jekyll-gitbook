---
description: >-
  FlutterVision uses Computer Vision to understand a Figma Project and convert
  it into an application. That's why paying attention to some details on Figma
  is so important.
---

# Good practices on Figma to get a better result

### How to prepare your Figma Project&#x20;

#### **Rename components**&#x20;

Choosing the best names to components (e.g. Frames, Buttons, etc.) can help you to get a better organization in your project. FlutterVision will import all names, in this way it will be easier to identify and make changes in those components. You can also use the component type in the name, like "Login\_Button", "Services\_Frame" and "Email\_Edit".&#x20;

****

#### **Use Frames and Groups**&#x20;

Boxes into boxes: this is how we build applications. So, when preparing your Figma project, it's important to create frames (this one is the best way) and groups to get a great "application tree".

![](https://lh4.googleusercontent.com/OZynuihCnxDwk--NyeVXTAgKPGiPM6PUnj1xHFO3tXwWAdREAvbd33N6v5RJdqS-OGQEl8vqnq-L2K8AlTtoGW1WlXbh24hfD81jmMXOZlH0exX5OCfn5l\_epGrERs3X98lAt\_I)

****

#### **Status bar and home indicator**

Since it's not necessary to code the status bar and the home indicator, this is not necessary on the Figma project. If it does, you can delete it before going to FlutterVision.

#### **Group vectors**

If you are working with a lot of vectors that compose the same image, remember to group it. In this way, FlutterVision will identify it as one component.

#### **Alignments**

Figma has a lot of options in terms of Alignments. If you are building a mobile application, it's important to review each frame's alignments, from parents to children. Access the "Auto Layout" properties to analyze the alignments, those will be imported as Stack Layout on FlutterVision. When there isn't Auto Layout, our tool will understand it as Relative Layout.&#x20;

{% hint style="info" %}
TIP: you can check the page behavior by resizing it. Figma will automatically update the component's sizes to adapt them to the screen.&#x20;
{% endhint %}

![](https://lh4.googleusercontent.com/BqOa6UP0pH2q-ltsaYhZm6F0tqsqsMFej3TYzQI5I9sQ-pubSOLZoliUHX8uUtyME5GXWuHDjJrQ2ctz3iWZUog-G3f4seMrkWC0bi5LrHPBxAzDo1ypIiN6SjxavKY22Tm9rmg)

#### **Constraints and Resizing**

Constraints and Resizing are also important when we are considering the user experience. So, it's important to check the selected options to ensure that the frames are having the expected behavior. Choose between Fill, Fixed**,** and Hug Contents.

{% hint style="info" %}
TIP: you can check the page behavior by resizing it. Figma will automatically update the component's sizes to adapt them to the screen.&#x20;
{% endhint %}

#### **Navigation**

You can use the navigation flow from Figma to import it to FlutterVision. In this way, navigation between screens will be already setted up.

![](https://lh3.googleusercontent.com/rSwiBocBZgpdNRFyUsXKlae4aInRKg0VRS3I-ljZOcLZNdx9H70Wmab947sN7nh0NQv1b3CmZ3sCVpiermMeU7c2tGqPCO\_td1X7z6yf9t1rmryXRhyQNkPmOGFBi6TJfhK5mQE)

#### **Delete unnecessary components**

When we are creating Figma projects, it is common to add some components, like frames, that we don't need. So, remember to delete those components. If you see a lot of strange boxes on Flutter Vision, there is a huge chance there will be an unnecessary components problem. Also, avoid using Invisible components.

#### **Color Fill properties**

Check each component color fill property. Remember that screens have their own color and layers can have different ones. You can also use the transparency option.

#### Avoid components out of screens

Please, do not use components or images which is using spaces outside of screens. Example:

![](<../.gitbook/assets/Screen Shot 2022-03-30 at 16.11.09.png>)

#### Let only one page on the Figma project

Avoid having more than one page on the Figma project. You may have only the page with the screens. At this same page, you can set up the navigation between the screens (on Figma this feature is called as Prototype). &#x20;

{% hint style="info" %}
Remeber, one Figma page. Not screens.
{% endhint %}

![](<../.gitbook/assets/Screen Shot 2022-03-30 at 16.16.04.png>)

#### Avoid lines with height = 0

The line should have at least 1 px. If you use a line with height = 0, tha AI will not be able to import the project.&#x20;

![](<../.gitbook/assets/Screen Shot 2022-03-30 at 16.19.23.png>)
