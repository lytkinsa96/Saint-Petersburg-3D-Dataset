# Saint Petersburg 3D: Creating a Large-Scale Hybrid Mobile LiDAR Point Cloud Dataset for Geospatial Applications

This repository presents the Saint Petersburg 3D Dataset, a comprehensive and large-scale point cloud dataset specifically designed for outdoor scene semantic segmentation in geospatial applications. The dataset encompasses both real-world and synthetic subsets, totaling 68 million points, acquired by real and virtual sensors with identical characteristics.

## Paper

Saint Petersburg 3D: Creating a Large-Scale Hybrid Mobile LiDAR Point Cloud Dataset for Geospatial Applications introduces the Saint Petersburg 3D dataset. In this research, we aimed to develop a new and diverse point cloud dataset tailored for outdoor scene semantic segmentation tasks in geospatial applications. While numerous publicly available datasets focus on autonomous driving, our dataset fills the gap by addressing the specific requirements of geospatial applications.

The Saint Petersburg 3D dataset comprises two subsets: a real-world subset containing 34 million points and a synthetic subset with an additional 34 million points. The real-world data was collected using mobile LiDAR sensors, capturing the three-dimensional geometry and appearance of outdoor scenes in Saint Petersburg. The synthetic subset was generated using virtual sensors, ensuring consistency in characteristics with the real-world subset.

To facilitate semantic segmentation tasks, we propose an original classification scheme consisting of 10 universal object categories. This scheme enables the division of any dense outdoor mobile LiDAR point cloud scene into these categories, enhancing the dataset's usefulness for various geospatial applications.

The paper describes the evaluation procedure for semantic segmentation of point clouds in geospatial applications. Additionally, an experiment was conducted using the Kernel Point Fully Convolution Neural Network (KPConv) model trained on the proposed dataset. The results demonstrated an impressive overall mean Intersection over Union (mIoU) of 92.56%, highlighting the efficacy of deep learning models for point cloud semantic segmentation within the context of the proposed classification scheme.   

## License

Saint Petersburg 3D is released under the [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license. 

## Download

Dataset can be downloaded at [Yandex 360](https://disk.yandex.ru/d/Zl9_DhNyD9S-yQ)

## Contact

Thank you for your interest in the large-scale point cloud dataset creation. We hope this resource proves valuable for your research and development endeavors!

For any questions, suggestions, or issues related to this repository or the dataset, feel free to contact [Lytkin Sergey](mailto:lytkin_sa@spbstu.ru). We appreciate your feedback and support!

## Citation

If you use the Saint Petersburg 3D dataset or refer to the research presented in the paper, please cite the following:

```
@article{#TODO,
    Author={#TODO},
    Title={{Saint Petersburg 3D}: Creating a Large-Scale Hybrid Mobile LiDAR Point Cloud Dataset for Geospatial Applications},
    Journal={#TODO},
    year={2023}
}
```
