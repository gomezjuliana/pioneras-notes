# Agile Testing

Lizet's slides: [here](http://slides.com/lizetjaramillo/agiletesting#/)

### Kanban
- very modifi-able

### XP
- stands out b/c client satisfaction is most important
- clients write their own user stories

### Scrum 
- most popular b/c it's light and easy to understand
- hard to master though b/c clients are always right but don't have clear ideas

### Testing Manifesto
- test throughout the process
- prevent errors as much as possible so we don't find them
- understand what the client really needs
- create the best system w/o bugs
- responsibility falls on the team to make sure it's good quality
- reduce documentation but include it  

:sparkle: agile testing works from the bottom up and automates as much as possible

### Resources
[Manifesto for Agile Software Development](http://agilemanifesto.org/iso/en/manifesto.html)

# Angular

Slides: *to be added*

- works with TypeScript or Javascript
- has components, this helps scale easier b/c you can pick and choose which components change w/o changing absolutely everything
- example: youtube copy, components: play bar, cards, header, side bar
- components can be inside components

### How to define components
- component is a mix of logic(behaviour) and HTML
- define class then decorators (define what the class does) - @ w/ metadata
- angular lets you extend HTML by creating new element tags
- one class per component  

:sparkle: *plnker.co -> like CodePen but for JS frameworks*

### Directives
1. Components
2. structural -> lets you extend HTML and how it acts
3. Attribute -> paint how selector will look (style) (mix logic with style)

### Data Binding
- passing data from components to view and visa versa
- lets changes happen on the DOM and changes any elements those changes affect

### Modules
- all components have a root module
- classes go in modules
- imports are the things you're bringing in from Angular's core
- declarations are the components that you're bringing in from your app (as many as you want)
- boostrap - this component is the very first that loas (only one)

### Resources
- [repo](https://github.com/eseguro/meetup-pioneras)
- Tour of Heros, official documentation