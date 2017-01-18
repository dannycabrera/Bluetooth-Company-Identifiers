# Bluetooth Company Identifiers
Bluetooth company identifiers from Bluetooth Special Interest Group (SIG)

=============
![bluetoothLogo](bluetoothLogo.png)

C# class to help pull company values. Data pulled from: https://www.bluetooth.com/specifications/assigned-numbers/company-identifiers

```csharp
// Examples to return Company "Apple, Inc." (76 - 0x004C)
BluetoothCompany example1 = new BluetoothCompanies().List.Where(c => c.CompanyId == 76).FirstOrDefault();
BluetoothCompany example2 = new BluetoothCompanies().List.Where(c => c.CompanyId == 0x004C).FirstOrDefault();
BluetoothCompany example3 = new BluetoothCompanies().List.Where(c => c.Company == "Apple, Inc.").FirstOrDefault();
```
