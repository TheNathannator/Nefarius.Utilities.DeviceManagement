# DriverMeta

Namespace: Nefarius.Utilities.DeviceManagement.Drivers

Driver meta data fetched from the registry.

```csharp
public sealed class DriverMeta
```

Inheritance [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object) → [DriverMeta](./nefarius.utilities.devicemanagement.drivers.drivermeta.md)

## Properties

### **DriverDate**

Gets the date of the driver.

```csharp
public DateTime DriverDate { get; internal set; }
```

#### Property Value

[DateTime](https://docs.microsoft.com/en-us/dotnet/api/system.datetime)<br>

### **DriverDescription**

Gets the description the device got from the function driver.

```csharp
public string DriverDescription { get; internal set; }
```

#### Property Value

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)<br>

### **DriverVersion**

Gets the driver version.

```csharp
public Version DriverVersion { get; internal set; }
```

#### Property Value

[Version](https://docs.microsoft.com/en-us/dotnet/api/system.version)<br>

### **InfPath**

Gets the active INF name/sub-path. Typically resides in C:\Windows\INF.

```csharp
public string InfPath { get; internal set; }
```

#### Property Value

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)<br>

### **InfSection**

Gets the section of the INF which applied on driver installation.

```csharp
public string InfSection { get; internal set; }
```

#### Property Value

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)<br>

### **MatchingDeviceId**

Gets the device ID this driver is active on.

```csharp
public string MatchingDeviceId { get; internal set; }
```

#### Property Value

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)<br>

### **ProviderName**

Gets the provider (manufacturer) name of the driver.

```csharp
public string ProviderName { get; internal set; }
```

#### Property Value

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)<br>
