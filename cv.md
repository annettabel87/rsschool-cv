# Repeshko Anna #

# Frontend Developer #

---

## __Contacts__
- Address: Russia
- e-mail: annettabel@rambler.ru
- phone: +79129321359
- github: [Annettabel87](https://github.com/annettabel87)
- telegram: @Annettabel 
- LinkedIn: https://www.linkedin.com/in/anna-repeshko/

---
## Skils ##

- HTML/CSS
- Javascript
- Typescript
- Git
- Webpack
- React
- Redux, Redux Toolkit
- Cartography programs: MapInfo, ArcGIS, AutoCAD
- English A2

---
## About me ##

I have always dreamed of being a programmer. And finally decided. I hope my love of learning and new things will help me.

---
## Education ##

### 2004-2009 ###

**Nizhnevartovsk state university**, geography, gis mapping

### 2020 ###

**CS50**

### 2021 -2022 ###

**RS School**, JS / FRONT-END/ React
## Work experience ##

### 2012-2021 OOO Zemleustroitelnoe predpriyatie,
engineer surveyor (geodesist)

### 2009-2012 MUP Zemleustroitelnoe predpriyatie,
engineer surveyor (geodesist)

---
## __Code Example__
```
const Modal: FC<IModalProps> = React.memo(({ children, open }: IModalProps) => {
  const domNode = document.getElementById('portal');
  const element = document.createElement('div');
  useEffect(() => {
    domNode?.appendChild(element);
    return () => {
      domNode?.removeChild(element);
    };
  });

  return open ? ReactDom.createPortal(children, element) : null;
});
```
---
## examples of work ##
- https://annettabel87.github.io/social-network/
- https://annettabel87-react-redux.netlify.app/
- https://project-management-app-71.netlify.app/
