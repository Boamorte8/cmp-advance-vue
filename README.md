# Vue Components Advance

In this project I will learn about components advanced on Vue

## Learned things

- Component registration
  - Global registration is for components that will be used on multiple places
  - Local registration is for components that will be used locally on one component
- Scoped styles: You need to add scoped like an attribute on style tag for the styles will be applied only to that component. If is no-added then the styles will be applied globally
- Slots: is the feature of Vue for project inside a component the content that you put inside the tags of that component (Like content projection in Angular)
  - You can have named slot to have some portions of slot in different places
  - You can define content to be projected like default, only put the default content inside the slot tag
  - The shorthand for v-slot: is '#'
  - You can pass data to the slots to be displayed in the content that define the slot
- Dynamic Components: when you need to display a component depending on a condition but without to use if statements
  - keep-alive is a tag is a good feature when you need to keep the state of a component even that component is destroyed
- Teleport: is a feature to send a piece of html to other place in the html tree. For example if you have in a component a dialog, you can send it to the body tag
- Fragments is the feature that allow to components in Vue 3 to have multiples top level o roots tags
- 

## Differences with Vue 2

- Vue 2 you must to have in each component a root tag. In Vue 3 is not a must