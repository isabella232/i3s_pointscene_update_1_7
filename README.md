DRAFT Specification for Point Cloud Scene Layer: Service and Package Standard
===============================================

![App](./pcsl.jpeg "A Point Cloud layer rendered with RGB attributes.") A Point Cloud layer rendered with RGB attributes.

This repository hosts the DRAFT specification for Point Cloud Scene Layer (PCL).

- [point clouds](./profiles/pointclouds/docs/documentation.md) (e.g. large point data from LiDAR)


The above specification is planned to be included as part of  [Indexed 3d Scene Layer (I3S)](./format/Indexed%203d%20Scene%20Layer%20Format%20Specification.md) and [scene layer package (\*.slpk)](./format/Indexed%203d%20Scene%20Layer%20Format%20Specification.md) open format, as well as the specification for accessing I3S resources as [scene service REST](./service/SceneService.md) endpoints.

The Point Cloud Scene Layer specification currently utilizes the [LEPCC](https://github.com/esri/lepcc) (Limited Error Point Cloud Compression) algorithm for data compression which is released under an Apache License 2.0 license.

## Contributing

You are very much invited to fork this repository to a public or private repository and to send pull requests if you have ideas for improvements or have found bugs in this documentation. Creating a fork solely for this purpose
does not constitute the creation and distribution of a derivative work. Please see our [guidelines for  contributing](https://github.com/esri/contributing).

## License for indexed 3D scene format and REST endpoint specification

Copyright 2015 - 2018 Esri

This draft specification is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International Public License](https://creativecommons.org/licenses/by-nd/4.0/legalcode).
You can implement the specification in services, clients or processing tools without restrictions.

You may also extend or modify the standard using the built-in extension and profiling mechanisms, however modified or extended versions of the standard may not be redistributed. The standard may only be redistributed in its unmodified version, under the same license.

You are free to:

- Share — copy and redistribute the material in any medium or format for any purpose, even commercially.
- The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- No derivatives — If you remix, transform, or build upon the material, you may not distribute (see note below) the modified material.
- No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.


[](Esri Tags: I3S, PointCloud, Indexed 3D Scene Layer, Scene Layer, ArcGIS WebScene, Mesh-Pyramids, ArcGISOnline Scene Service, ArcGISServer, Scene Layer Package, SceneLayer, 3D Object, Point, IntegreatedMesh)
[](Esri Language: JavaScript)