<<<<<<< HEAD
<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g @nestjs/mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
=======
# sis257_sansa_desings
Sansa Designs es un emprendimiento localizado en Sucre – Bolivia, dedicado a la venta de productos textiles artesanales como carteras, billeteras, bolsos y cojines, elaborados principalmente con materiales naturales como lino, lana y yute.
La empresa funciona únicamente de manera virtual, utilizando redes sociales (Facebook, Instagram, TikTok) y una página web para difundir y vender sus productos. Nació en 2020 durante la pandemia y se consolidó en 2021, destacándose por la originalidad de sus diseños, la identidad cultural y la estética contemporánea.
Actualmente, enfrenta limitaciones en la gestión de proveedores, inventarios, ventas y reportes, ya que todos sus procesos se realizan de forma manual y dispersa. El objetivo del proyecto es desarrollar un sistema informático de gestión que permita automatizar y optimizar estos procesos, mejorando la eficiencia administrativa y la toma de decisiones.
Campos tentativos:
Usuarios: Almacena los datos de clientes y administradores, diferenciados por roles y credenciales de acceso.
Categorías: Define la clasificación de los productos (ejemplo: carteras, bolsos, cojines).
Productos: Contiene la información de los artículos disponibles en la tienda, su precio, stock y categoría.
Proveedores: Registra los datos de los proveedores y los materiales que suministran a la empresa.
Inventario: Controla las existencias de insumos y productos terminados, vinculados a proveedores.
Carrito: Representa la selección temporal de productos que un usuario añade antes de realizar un pedido.
carrito_productos: Tabla pivote que guarda los productos y cantidades asociados a un carrito.
Pedidos: Registra las compras confirmadas realizadas por los usuarios, con su estado y total.
pedido_productos: Tabla pivote que guarda los productos y cantidades asociados a un pedido específico.
Pagos: Almacena la información de las transacciones de un pedido, incluyendo método, monto y estado.
Reportes: Contiene indicadores generados automáticamente sobre ventas, inventario o proveedores.
Usuarios (id, nombre, apellidos, email, password, rol, fecha_creacion)
categorías (id, nombre, descripcion)
productos (id, nombre, descripcion, precio, stock, id_categoria, imagen_url)
proveedores (id, nombre, telefono, email, direccion, materiales)
inventario (id, nombre_item, tipo, cantidad, unidad_medida, id_proveedor)
carrito (id, id_usuario, creado_en, estado)
carrito_productos (id, id_carrito, id_producto, cantidad)
pedidos (id, id_usuario, total, estado, fecha_creacion)
pedido_productos (id, id_pedido, id_producto, cantidad, precio_unitario)
pagos (id, id_pedido, metodo, monto, estado, fecha_pago)
reportes (id, tipo, fecha_generacion, datos)
>>>>>>> 1bf3a3fa01424b163ccf088655f43719ec2eb8e8
