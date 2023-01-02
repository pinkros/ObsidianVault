
```cs
//Filsökvägar:

private static readonly string _jsonDirectory = Path.Combine(Environment.GetFolderPath(Environment.SpecialFolder.LocalApplicationData), "Den lelle butiken");

private static readonly string _jsonFile = Path.Combine(_jsonDirectory, "Products.json");


```