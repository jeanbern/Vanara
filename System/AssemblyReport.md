## Assembly report for Vanara.SystemServices.dll
### Enumerations
Enum | Description | Values
---- | ---- | ----
[Vanara.Diagnostics.BatteryStatus](https://github.com/dahall/Vanara/search?l=C%23&q=BatteryStatus) | Indicates the status of the battery. | NotPresent, Discharging, Idle, Charging
[Vanara.Diagnostics.EnergySaverStatus](https://github.com/dahall/Vanara/search?l=C%23&q=EnergySaverStatus) | Specifies the status of battery saver. | Disabled, Off, On
[Vanara.Diagnostics.JobLimit](https://github.com/dahall/Vanara/search?l=C%23&q=JobLimit) | The job limit type exceeded as communicated by a `Vanara.Diagnostics.JobNotificationEventArgs`. | PerJobUserTime, JobMemory, JobLowMemory, IoReadBytes, IoWriteBytes, RateControlTolerance, IoRateControlTolerance, NetRateControlTolerance
[Vanara.Extensions.NetworkInterfaceAccessType](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfaceAccessType) | The interface access type. | Loopback, Broadcast, PointToPoint, PointToMultiPoint
[Vanara.Extensions.NetworkInterfaceAdministrativeStatus](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfaceAdministrativeStatus) | Specifies the NDIS network interface administrative status, as described in RFC 2863. | Up, Down, Testing
[Vanara.Extensions.NetworkInterfaceConnectionType](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfaceConnectionType) | Specifies the NDIS network interface connection type. | Dedicated, Passive, Demand
[Vanara.Extensions.NetworkInterfaceDirectionType](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfaceDirectionType) | Specifies the NDIS network interface direction type. | SendReceive, SendOnly, ReceiveOnly
[Vanara.Extensions.NetworkInterfaceMediaType](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfaceMediaType) | The NDIS media type of a network interface. | Ethernet802_3, TokenRing, Fddi, Wan, LocalTalk, Dix, ArcnetRaw, Arcnet878_2, Atm, Wireless, IrDA, Broadcast, CoWAN, Ieee1394, InfiniBand, Tunnel, Native802_11, Loopback, WiMAX, IP
[Vanara.Extensions.NetworkInterfacePhysicalMedium](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfacePhysicalMedium) | The NDIS physical medium type. | Unspecified, WirelessLan, CableModem, PhoneLine, PowerLine, DSL, FibreChannel, Ieee1394, WirelessWan, Native802_11, Bluetooth, InfiniBand, WiMAX, UWB, Ethernet802_3, TokenRing, IrDA, WiredWAN, WiredCoWAN, Other
[Vanara.IO.PathEx.PathCharType](https://github.com/dahall/Vanara/search?l=C%23&q=PathCharType) | The type of character retrieved from `Vanara.IO.PathEx.GetCharType(System.Char)`. | Invalid, LongFileName, ShortFileName, Wildcard, Separator
[Vanara.Diagnostics.PowerCapabilities](https://github.com/dahall/Vanara/search?l=C%23&q=PowerCapabilities) | Specifies the power capabilities of a device. | PowerButtonPresent, SleepButtonPresent, LidPresent, SystemS1, SystemS2, SystemS3, SystemS4, SystemS5, HiberFilePresent, FullWake, VideoDimPresent, ApmPresent, UpsPresent, ThermalControl, ProcessorThrottle, FastSystemS4, Hiberboot, WakeAlarmPresent, AoAc, DiskSpinDown, AoAcConnectivitySupported, SystemBatteriesPresent, BatteriesAreShortTerm
[Vanara.Diagnostics.PowerSupplyStatus](https://github.com/dahall/Vanara/search?l=C%23&q=PowerSupplyStatus) | Represents the device's power supply status. | NotPresent, Inadequate, Adequate
[Vanara.Extensions.ProcessIntegrityLevel](https://github.com/dahall/Vanara/search?l=C%23&q=ProcessIntegrityLevel) | Values which define a processes integrity level. | Untrusted, Undefined, Low, Medium, High, System
[Vanara.Security.AccessControl.ServiceControllerAccessRights](https://github.com/dahall/Vanara/search?l=C%23&q=ServiceControllerAccessRights) | Defines the access rights to use when creating access and audit rules. | QueryConfig, ChangeConfig, QueryStatus, EnumerateDependents, Start, Stop, Continue, Interrogate, UserDefinedControl, Delete, ReadPermissions, Write, Read, Execute, ChangePermissions, TakeOwnership, AccessSystemSecurity, FullControl
[Vanara.ShareOfflineSettings](https://github.com/dahall/Vanara/search?l=C%23&q=ShareOfflineSettings) | Offline settings for a shared folder. | OnlySpecified, All, AllOptimized, None
### Interfaces
Interface | Description
---- | ----
[Vanara.Network.NetworkListManager.IEnumerableList<T>](https://github.com/dahall/Vanara/search?l=C%23&q=IEnumerableList<T>) | An enumerable list that supports a length and indexer.
[Vanara.INamedEntity](https://github.com/dahall/Vanara/search?l=C%23&q=INamedEntity) | An object that exposes a name.
### Classes
Class | Description
---- | ----
[Vanara.Computer](https://github.com/dahall/Vanara/search?l=C%23&q=Computer) | Represents a single connected (authenticated) computer.
[Vanara.Extensions.FileInfoExtension](https://github.com/dahall/Vanara/search?l=C%23&q=FileInfoExtension) | Extension methods for `System.IO.FileSystemInfo` and derived classes to facilitate retrieval of extended properties.
[Vanara.Diagnostics.IoCompletionPort](https://github.com/dahall/Vanara/search?l=C%23&q=IoCompletionPort) | Represents a system I/O completion port.
[Vanara.Diagnostics.Job](https://github.com/dahall/Vanara/search?l=C%23&q=Job) | Represents a system Job Object that allows groups of processes to be managed as a unit. Job objects are nameable, securable, sharable objects that control attributes of the processes associated with them. Operations performed on a job object affect all processes associated with the job object. Examples include enforcing limits such as working set size and process priority or terminating all processes associated with a job. For more information see <a href="https://docs.microsoft.com/en-us/windows/win32/procthread/job-objects">Job Objects</a>.
[Vanara.Diagnostics.JobEventArgs](https://github.com/dahall/Vanara/search?l=C%23&q=JobEventArgs) | Contains information about a job object message.
[Vanara.Diagnostics.JobHelper](https://github.com/dahall/Vanara/search?l=C%23&q=JobHelper) | Base class for other classes that support the `Vanara.Diagnostics.Job` object.
[Vanara.Diagnostics.JobLimits](https://github.com/dahall/Vanara/search?l=C%23&q=JobLimits) | Settings for `Vanara.Diagnostics.Job` that set limits for different runtime values.
[Vanara.Diagnostics.JobNotificationEventArgs](https://github.com/dahall/Vanara/search?l=C%23&q=JobNotificationEventArgs) | Contains information about a job object limit notification message.
[Vanara.Diagnostics.JobNotifications](https://github.com/dahall/Vanara/search?l=C%23&q=JobNotifications) | Settings for `Vanara.Diagnostics.Job` that set notification limits for different properties.
[Vanara.Diagnostics.JobSecurity](https://github.com/dahall/Vanara/search?l=C%23&q=JobSecurity) | Represents the security access rights of a job object.
[Vanara.Diagnostics.JobSettings](https://github.com/dahall/Vanara/search?l=C%23&q=JobSettings) | Settings related to job objects.
[Vanara.Diagnostics.JobStatistics](https://github.com/dahall/Vanara/search?l=C%23&q=JobStatistics) | Gets statistics for a job object.
[Vanara.Network.NetworkConnection](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkConnection) | Represents a single network connection. Wraps `Vanara.PInvoke.NetListMgr.INetworkConnection`.
[Vanara.Extensions.NetworkInterfaceExt](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkInterfaceExt) | Extension methods for various network related interfaces methods.
[Vanara.Network.NetworkListManager](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkListManager) | Provides a set of methods to perform network list management functions.
[Vanara.Network.NetworkProfile](https://github.com/dahall/Vanara/search?l=C%23&q=NetworkProfile) | Represents a wireless network profile
[Vanara.OpenFile](https://github.com/dahall/Vanara/search?l=C%23&q=OpenFile) | Represents an open file associated with a share.
[Vanara.IO.PathEx](https://github.com/dahall/Vanara/search?l=C%23&q=PathEx) | Performs operations on String instances that contain file or directory path information. These operations are performed in a cross-platform manner.
[Vanara.Diagnostics.PoweredDevice](https://github.com/dahall/Vanara/search?l=C%23&q=PoweredDevice) | Represents a device on the system that has power requirements.
[Vanara.Diagnostics.PoweredDeviceCollection](https://github.com/dahall/Vanara/search?l=C%23&q=PoweredDeviceCollection) | Retrieves the list, optionally filtered, of the powered devices on the system.
[Vanara.Diagnostics.PowerManager](https://github.com/dahall/Vanara/search?l=C%23&q=PowerManager) | Provides access to information about a device's battery and power supply status and configuration. This extends the capabilities Windows.System.Power.PowerManager to include more detail, schemes and devices.
[Vanara.Diagnostics.PowerScheme](https://github.com/dahall/Vanara/search?l=C%23&q=PowerScheme) | Represents a system power scheme (power plan).
[Vanara.Diagnostics.PowerSchemeCollection](https://github.com/dahall/Vanara/search?l=C%23&q=PowerSchemeCollection) | Represents a collection of all the power schemes available on the system.
[Vanara.Diagnostics.PowerSchemeGroup](https://github.com/dahall/Vanara/search?l=C%23&q=PowerSchemeGroup) | Represents a subgroup of a system power scheme (power plan).
[Vanara.Diagnostics.PowerSchemeGroupCollection](https://github.com/dahall/Vanara/search?l=C%23&q=PowerSchemeGroupCollection) | Represents a collection of all the subgroups available under a power scheme on the system.
[Vanara.Diagnostics.PowerSchemeSetting](https://github.com/dahall/Vanara/search?l=C%23&q=PowerSchemeSetting) | Represents a setting on a subgroup.
[Vanara.Diagnostics.PowerSchemeSettingCollection](https://github.com/dahall/Vanara/search?l=C%23&q=PowerSchemeSettingCollection) | Represents a collection of all settings for a subgroup and power scheme on the system.
[Vanara.Extensions.ProcessExtension](https://github.com/dahall/Vanara/search?l=C%23&q=ProcessExtension) | Extension methods for `System.Diagnostics.Process` for privileges, status, elevation and relationships.
[Vanara.Registry.RegistryEventMonitor.RegistryEventArgs](https://github.com/dahall/Vanara/search?l=C%23&q=RegistryEventArgs) | Argument used in `Vanara.Registry.RegistryEventMonitor` events.
[Vanara.Registry.RegistryEventMonitor](https://github.com/dahall/Vanara/search?l=C%23&q=RegistryEventMonitor) | Watches the Windows Registry for any changes.
[Vanara.Security.AccessControl.ServiceControllerAccessRule](https://github.com/dahall/Vanara/search?l=C%23&q=ServiceControllerAccessRule) | Represents an abstraction of an access control entry (ACE) that defines an access rule for a service.
[Vanara.Security.AccessControl.ServiceControllerAuditRule](https://github.com/dahall/Vanara/search?l=C%23&q=ServiceControllerAuditRule) | Represents an abstraction of an access control entry (ACE) that defines an audit rule for a service.
[Vanara.Extensions.ServiceControllerExtension](https://github.com/dahall/Vanara/search?l=C%23&q=ServiceControllerExtension) | Extension methods for `System.ServiceProcess.ServiceController`.
[Vanara.Security.AccessControl.ServiceControllerSecurity](https://github.com/dahall/Vanara/search?l=C%23&q=ServiceControllerSecurity) | Represents the access control and audit security for a service.
[Vanara.ShareConnection](https://github.com/dahall/Vanara/search?l=C%23&q=ShareConnection) | Represents a connection to a shared device.
[Vanara.SharedDevice](https://github.com/dahall/Vanara/search?l=C%23&q=SharedDevice) | Represents a shared device on a computer.
[Vanara.SharedDevices](https://github.com/dahall/Vanara/search?l=C%23&q=SharedDevices) | Represents all the shared devices on a computers.
[Vanara.Diagnostics.SystemShutdown](https://github.com/dahall/Vanara/search?l=C%23&q=SystemShutdown) | Provides access to system shutdown, restart, lock and notifications.
[Vanara.IO.Wow64Redirect](https://github.com/dahall/Vanara/search?l=C%23&q=Wow64Redirect) | Suspends File System Redirection if found to be in effect. Effectively, this calls <c>IsWow64Process</c> to determine state and then disables redirection using <c>Wow64DisableWow64FsRedirection</c>. It then reverts redirection at disposal using <c>Wow64RevertWow64FsRedirection</c>.
