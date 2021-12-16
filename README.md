# vem-indicator-3D-dataset
Datasets used for "A quality indicator for polyhedral meshes in the Virtual Element Method" by T. Sorgente, S. Biasotti, G. Manzini and M. Spagnuolo.
These datasets have been created within the mesh generation framework presented in the Section 4 of the paper.

## Content
Each .zip file contains a dataset made of five meshes with decreasing mesh size; some of them are divided in two parts due to the file size limitations of github.

Each mesh is saved in the REGN_FACE format, which consists in a .node file, containing the vertices coordinates:
_vertex_id   x_coord  y_coord z_coord_
and a .ele file, containing informations about the elements with the following structure:
_element_id  n_of_faces
    face_id   n_face_verts  face_verts_ids_

## Citing us
If you use one or more datasets in your academic projects, please consider citing the original paper using the following BibTeX entry:

```
@misc{
}
```

## Acknowldegment
This research has been supported bt the ERC Project CHANGE (https://cordis.europa.eu/project/id/694515), which has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme (grant agreement No 694515).
