<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/CoordinateConverters/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/CoordinateConverters/MainWindow.xaml))**
<!-- default file list end -->
# How to load Cartesian data to a geographic map


This example demonstrates how to load Cartesian map data to a geographic map.


<h3>Description</h3>

If data contains a <em>*.PRJ</em> file, it is possible to use the&nbsp;<a href="https://documentation.devexpress.com/#wpf/DevExpressXpfMapShapefileDataAdapter_LoadPrjFiletopic">LoadPrjFile</a> method if coordinate system&nbsp;has not&nbsp;been loaded automatically.<br />If your data does not contain a&nbsp;<em>*.PRJ</em> file, create an&nbsp;<a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapCartesianSourceCoordinateSystemtopic">CartesianSourceCoordinateSystem</a> object, specify its&nbsp;<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapCartesianSourceCoordinateSystem_MeasureUnittopic">MeasureUnit</a> and <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapSourceCoordinateSystem_CoordinateConvertertopic">CoordinateConverter </a>properties. Then, assign the object to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapShapefileDataAdapter_SourceCoordinateSystemtopic">ShapefileDataAdapter.SourceCoordinateSystem</a>&nbsp;property.<br /><br />

<br/>


