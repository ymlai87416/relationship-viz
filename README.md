# relationship-viz

## Background

Just a simple program to allow me to load data and visualize it

### Dataset
Sample dataset

* PMP knowledge area and process group

Or you can load your dataset in the following format

* An Excel file

* Some sheet represent an entity
    The color of entity is assign in the tab20, which is defined in https://www.analyticsvidhya.com/blog/2020/09/colormaps-matplotlib/

* Some sheet represent relationship (directional, unless marked as B)

### Query

There are 3 types

* select entityA, entityB, ... entityN

    if you want to only see relationship between a specific group of entities, please add this

* from a to b

Only intermediate node are shown

* from a level N

Show graph which only N level down a, and 'a' as the 1st level 

* to b level N 

Show graph which only N level up 'b', and 'b' is the Nth level

Default is all, which show all the node


## Project status

- [x] Define requirement
- [x] Make sample dataset PMP
- [ ] Development
- [ ] Test
- [ ] put into production

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
