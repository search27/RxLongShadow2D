# RxLongShadow2D
RxLongShadow2D


Support By [ Cloud Rx (<a href='https://rxapis.com'>https://rxapis.com</a>) ].
* Testing is available until the end of the year.

## Table of Contents

- [Rx Long Shadow 2D](#rx-long-shadow-2d)
    - [CreateCanvas](#point-3d)
    - [POINT3D](#point-3d)
    - [Quadrangle](#point-3d)
    - [Shadow](#point-3d)


## Rx Long Shadow 2D
* Create Long Shadow into 2d Canvas

### CreateCanvas
* Create Canvas
* func CreateCanvas : (target, canvasCount, resize) return (Array) canvas

```javascript
const target = document.getElementById('testDom');
const canvas = RxLongShadow2D.CreateCanvas(target, 2, true);
```

### POINT3D
* constructor

```javascript
const point3d = new RxDriveLongShadow2D.POINT3D(x, y, z);
```

### Quadrangle
* constructor
* new RxLongShadow2D.Quadrangle( parent, x, y, width, height, color )
* func draw : (ctx)
* func update : ()
* func GetVertexes : () return Array<POINT3D>

```javascript
const poly = new RxLongShadow2D.Quadrangle(undefined, x, y, size, size, color);
```

### Shadow
* constructor
* new RxLongShadow2D.Shadow()
* func draw : (ctx)
* func update : ()
* func SetLight : ({x, y})
* func SetColor : (String)
* func SetParentVertexes : (Array<POINT3D>)

```javascript
const shadow = new RxLongShadow2D.Shadow();
```
<img width="1659" alt="스크린샷 2024-09-10 오후 2 50 33" src="https://github.com/user-attachments/assets/f6d75346-7ed9-49a7-bfe2-a6f1af5010b0">


