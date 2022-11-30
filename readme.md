Just open powershell in admin mode

run:

`Set-NetAdapterAdvancedProperty -InterfaceDescription 'Hyper-V Virtual Ethernet Adapter' -DisplayName 'Large Send Offload Version 2 (IPv4)' -DisplayValue 'Disabled'`
<br>and<br>
`Set-NetAdapterAdvancedProperty -InterfaceDescription 'Hyper-V Virtual Ethernet Adapter' -DisplayName 'Large Send Offload Version 2 (IPv6)' -DisplayValue 'Disabled' `
