# Documentation

Dokumentasi untuk base project portal sekawan

## Library

- Bootstrap
- Popover (If wants to use)

## Directory Structure

Berikut adalah Directory Structure dari sample project ini.

```
project/
|-- assets/
|   |-- css/
|   |-- js/
|   |-- fonts/
|   |-- images/
|
|-- index.html
```

### index.html

index html berisikan base html menggunakan [Bootstrap](https://getbootstrap.com)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>sample</title>

    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <h1 class="">Hello, world!</h1>

    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
      crossorigin="anonymous"
    ></script>

    <!-- un comment jika ingin menggunakan dropdowns, popovers, atau tooltips -->
    <!-- <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script> -->
  </body>
</html>
```

### assets/

folder assets dibagi menjadi 4 yaitu :

#### images/

berisikan assets gambar yang akan digunakan

#### css/

berisikan file css yang akan digunakan, bila ingin menggunakan font atau membuat styling yang tidak ada ada bootstrap

#### js/

berisikan file javascript, dapat berisikan function onclick atau yang lainnya