# TezJS with primevue

- PrimeVue is a comprehensive UI library for Vue featuring a rich set of 90+ components.
- We can use primevue with the Tezjs through the below steps.
- Create a new TezJS project

```
 npm create tez@latest
```

- Install the below package for primevue

```
npm install primevue@^3.17.0 --save
```

- Now add it as a plugin, make a plugins directory and add index.ts inside it and add the below code
```
/plugins/index.ts

import PrimeVue from 'primevue/config'

export default function(vue:any){
    vue.use(PrimeVue)
}
```

- To work with the grid system in primevue, install prime flex with the below command

```
npm install primeflex
```

- To apply primeflex CSS and primevue CSS, import the below css files in your index.css file which can be found under the assets directory

```
/asstes/index.css

@import '/node_modules/primeflex/primeflex.css';
@import '/node_modules/primevue/resources/primevue.css';
@import '/node_modules/primevue/resources/primevue.min.css';
```

- To work with different color themes, import the below .css files in index.css as mentioned below

```
/asstes/index.css

@import '/node_modules/primevue/resources/themes/saga-blue/theme.css';
@import '/node_modules/primevue/resources/themes/saga-purple/theme.css';
@import '/node_modules/primevue/resources/themes/md-light-indigo/theme.css'
```

- It's done with tezjs. Now, you can use it inside your project.

- In the current project all components and pages are designed with a primevue framework.


**Note** : 
- For more information related to primevue, visit: https://www.primefaces.org/primevue/
- For more information related to primeflex and color themes, visit: https://www.primefaces.org/primeflex/