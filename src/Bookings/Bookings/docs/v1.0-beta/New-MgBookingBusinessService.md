---
external help file:
Module Name: Microsoft.Graph.Bookings
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.bookings/new-mgbookingbusinessservice
schema: 2.0.0
---

# New-MgBookingBusinessService

## SYNOPSIS
All the services offered by this business.
Read-only.
Nullable.

## SYNTAX

### CreateExpanded (Default)
```
New-MgBookingBusinessService -BookingBusinessId <String> [-AdditionalInformation <String>]
 [-AdditionalProperties <Hashtable>] [-CustomQuestions <IMicrosoftGraphBookingQuestionAssignment[]>]
 [-DefaultDuration <TimeSpan>] [-DefaultLocation <IMicrosoftGraphLocation>] [-DefaultPrice <Double>]
 [-DefaultPriceType <String>] [-DefaultReminders <IMicrosoftGraphBookingReminder[]>] [-Description <String>]
 [-DisplayName <String>] [-Id <String>] [-IsHiddenFromCustomers] [-IsLocationOnline]
 [-MaximumAttendeesCount <Int32>] [-Notes <String>] [-PostBuffer <TimeSpan>] [-PreBuffer <TimeSpan>]
 [-SchedulingPolicy <IMicrosoftGraphBookingSchedulingPolicy>] [-SmsNotificationsEnabled]
 [-StaffMemberIds <String[]>] [-WebUrl <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgBookingBusinessService -BookingBusinessId <String> -BodyParameter <IMicrosoftGraphBookingService>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgBookingBusinessService -InputObject <IBookingsIdentity> -BodyParameter <IMicrosoftGraphBookingService>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgBookingBusinessService -InputObject <IBookingsIdentity> [-AdditionalInformation <String>]
 [-AdditionalProperties <Hashtable>] [-CustomQuestions <IMicrosoftGraphBookingQuestionAssignment[]>]
 [-DefaultDuration <TimeSpan>] [-DefaultLocation <IMicrosoftGraphLocation>] [-DefaultPrice <Double>]
 [-DefaultPriceType <String>] [-DefaultReminders <IMicrosoftGraphBookingReminder[]>] [-Description <String>]
 [-DisplayName <String>] [-Id <String>] [-IsHiddenFromCustomers] [-IsLocationOnline]
 [-MaximumAttendeesCount <Int32>] [-Notes <String>] [-PostBuffer <TimeSpan>] [-PreBuffer <TimeSpan>]
 [-SchedulingPolicy <IMicrosoftGraphBookingSchedulingPolicy>] [-SmsNotificationsEnabled]
 [-StaffMemberIds <String[]>] [-WebUrl <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
All the services offered by this business.
Read-only.
Nullable.

## EXAMPLES

## PARAMETERS

### -AdditionalInformation
Additional information that is sent to the customer when an appointment is confirmed.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Represents a particular service offered by a booking business.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBookingService
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BookingBusinessId
key: id of bookingBusiness

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CustomQuestions
Contains the set of custom questions associated with a particular service.
To construct, please use Get-Help -Online and see NOTES section for CUSTOMQUESTIONS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBookingQuestionAssignment[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultDuration
The default length of the service, represented in numbers of days, hours, minutes, and seconds.
For example, P11D23H59M59.999999999999S.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultLocation
location
To construct, please use Get-Help -Online and see NOTES section for DEFAULTLOCATION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphLocation
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultPrice
The default monetary price for the service.

```yaml
Type: System.Double
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultPriceType
Represents the type of pricing of a booking service.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultReminders
The default set of reminders for an appointment of this service.
The value of this property is available only when reading this bookingService by its ID.
To construct, please use Get-Help -Online and see NOTES section for DEFAULTREMINDERS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBookingReminder[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
A text description for the service.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
A name for the derived entity, which interfaces with customers.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IBookingsIdentity
Parameter Sets: CreateViaIdentity, CreateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsHiddenFromCustomers
True means this service is not available to customers for booking.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsLocationOnline
True indicates that the appointments for the service will be held online.
Default value is false.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaximumAttendeesCount
The maximum number of customers allowed in a service.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Notes
Additional information about this service.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PostBuffer
The time to buffer after an appointment for this service ends, and before the next customer appointment can be booked.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PreBuffer
The time to buffer before an appointment for this service can start.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SchedulingPolicy
This type represents the set of policies that dictate how bookings can be created in a Booking Calendar.
To construct, please use Get-Help -Online and see NOTES section for SCHEDULINGPOLICY properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBookingSchedulingPolicy
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SmsNotificationsEnabled
True indicates SMS notifications can be sent to the customers for the appointment of the service.
Default value is false.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StaffMemberIds
Represents those staff members who provide this service.

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WebUrl
The URL a customer uses to access the service.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IBookingsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBookingService

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBookingService

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphBookingService>: Represents a particular service offered by a booking business.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: A name for the derived entity, which interfaces with customers.
  - `[Id <String>]`: Read-only.
  - `[AdditionalInformation <String>]`: Additional information that is sent to the customer when an appointment is confirmed.
  - `[CustomQuestions <IMicrosoftGraphBookingQuestionAssignment[]>]`: Contains the set of custom questions associated with a particular service.
    - `[IsRequired <Boolean?>]`: Indicates whether it is mandatory to answer the custom question.
    - `[QuestionId <String>]`: If it is mandatory to answer the custom question.
  - `[DefaultDuration <TimeSpan?>]`: The default length of the service, represented in numbers of days, hours, minutes, and seconds. For example, P11D23H59M59.999999999999S.
  - `[DefaultLocation <IMicrosoftGraphLocation>]`: location
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Address <IMicrosoftGraphPhysicalAddress>]`: physicalAddress
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[City <String>]`: The city.
      - `[CountryOrRegion <String>]`: The country or region. It's a free-format string value, for example, 'United States'.
      - `[PostOfficeBox <String>]`: The post office box number.
      - `[PostalCode <String>]`: The postal code.
      - `[State <String>]`: The state.
      - `[Street <String>]`: The street.
      - `[Type <String>]`: physicalAddressType
    - `[Coordinates <IMicrosoftGraphOutlookGeoCoordinates>]`: outlookGeoCoordinates
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Accuracy <Double?>]`: The accuracy of the latitude and longitude. As an example, the accuracy can be measured in meters, such as the latitude and longitude are accurate to within 50 meters.
      - `[Altitude <Double?>]`: The altitude of the location.
      - `[AltitudeAccuracy <Double?>]`: The accuracy of the altitude.
      - `[Latitude <Double?>]`: The latitude of the location.
      - `[Longitude <Double?>]`: The longitude of the location.
    - `[DisplayName <String>]`: The name associated with the location.
    - `[LocationEmailAddress <String>]`: Optional email address of the location.
    - `[LocationType <String>]`: locationType
    - `[LocationUri <String>]`: Optional URI representing the location.
    - `[UniqueId <String>]`: For internal use only.
    - `[UniqueIdType <String>]`: locationUniqueIdType
  - `[DefaultPrice <Double?>]`: The default monetary price for the service.
  - `[DefaultPriceType <String>]`: Represents the type of pricing of a booking service.
  - `[DefaultReminders <IMicrosoftGraphBookingReminder[]>]`: The default set of reminders for an appointment of this service. The value of this property is available only when reading this bookingService by its ID.
    - `[Message <String>]`: The message in the reminder.
    - `[Offset <TimeSpan?>]`: The amount of time before the start of an appointment that the reminder should be sent. It's denoted in ISO 8601 format.
    - `[Recipients <String>]`: 
  - `[Description <String>]`: A text description for the service.
  - `[IsHiddenFromCustomers <Boolean?>]`: True means this service is not available to customers for booking.
  - `[IsLocationOnline <Boolean?>]`: True indicates that the appointments for the service will be held online. Default value is false.
  - `[MaximumAttendeesCount <Int32?>]`: The maximum number of customers allowed in a service.
  - `[Notes <String>]`: Additional information about this service.
  - `[PostBuffer <TimeSpan?>]`: The time to buffer after an appointment for this service ends, and before the next customer appointment can be booked.
  - `[PreBuffer <TimeSpan?>]`: The time to buffer before an appointment for this service can start.
  - `[SchedulingPolicy <IMicrosoftGraphBookingSchedulingPolicy>]`: This type represents the set of policies that dictate how bookings can be created in a Booking Calendar.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AllowStaffSelection <Boolean?>]`: True if to allow customers to choose a specific person for the booking.
    - `[MaximumAdvance <TimeSpan?>]`: Maximum number of days in advance that a booking can be made. It follows the ISO 8601 format.
    - `[MinimumLeadTime <TimeSpan?>]`: The minimum amount of time before which bookings and cancellations must be made. It follows the ISO 8601 format.
    - `[SendConfirmationsToOwner <Boolean?>]`: True to notify the business via email when a booking is created or changed. Use the email address specified in the email property of the bookingBusiness entity for the business.
    - `[TimeSlotInterval <TimeSpan?>]`: Duration of each time slot, denoted in ISO 8601 format.
  - `[SmsNotificationsEnabled <Boolean?>]`: True indicates SMS notifications can be sent to the customers for the appointment of the service. Default value is false.
  - `[StaffMemberIds <String[]>]`: Represents those staff members who provide this service.
  - `[WebUrl <String>]`: The URL a customer uses to access the service.

CUSTOMQUESTIONS <IMicrosoftGraphBookingQuestionAssignment[]>: Contains the set of custom questions associated with a particular service.
  - `[IsRequired <Boolean?>]`: Indicates whether it is mandatory to answer the custom question.
  - `[QuestionId <String>]`: If it is mandatory to answer the custom question.

DEFAULTLOCATION <IMicrosoftGraphLocation>: location
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Address <IMicrosoftGraphPhysicalAddress>]`: physicalAddress
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[City <String>]`: The city.
    - `[CountryOrRegion <String>]`: The country or region. It's a free-format string value, for example, 'United States'.
    - `[PostOfficeBox <String>]`: The post office box number.
    - `[PostalCode <String>]`: The postal code.
    - `[State <String>]`: The state.
    - `[Street <String>]`: The street.
    - `[Type <String>]`: physicalAddressType
  - `[Coordinates <IMicrosoftGraphOutlookGeoCoordinates>]`: outlookGeoCoordinates
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Accuracy <Double?>]`: The accuracy of the latitude and longitude. As an example, the accuracy can be measured in meters, such as the latitude and longitude are accurate to within 50 meters.
    - `[Altitude <Double?>]`: The altitude of the location.
    - `[AltitudeAccuracy <Double?>]`: The accuracy of the altitude.
    - `[Latitude <Double?>]`: The latitude of the location.
    - `[Longitude <Double?>]`: The longitude of the location.
  - `[DisplayName <String>]`: The name associated with the location.
  - `[LocationEmailAddress <String>]`: Optional email address of the location.
  - `[LocationType <String>]`: locationType
  - `[LocationUri <String>]`: Optional URI representing the location.
  - `[UniqueId <String>]`: For internal use only.
  - `[UniqueIdType <String>]`: locationUniqueIdType

DEFAULTREMINDERS <IMicrosoftGraphBookingReminder[]>: The default set of reminders for an appointment of this service. The value of this property is available only when reading this bookingService by its ID.
  - `[Message <String>]`: The message in the reminder.
  - `[Offset <TimeSpan?>]`: The amount of time before the start of an appointment that the reminder should be sent. It's denoted in ISO 8601 format.
  - `[Recipients <String>]`: 

INPUTOBJECT <IBookingsIdentity>: Identity Parameter
  - `[BookingAppointmentId <String>]`: key: id of bookingAppointment
  - `[BookingBusinessId <String>]`: key: id of bookingBusiness
  - `[BookingCurrencyId <String>]`: key: id of bookingCurrency
  - `[BookingCustomQuestionId <String>]`: key: id of bookingCustomQuestion
  - `[BookingCustomerBaseId <String>]`: key: id of bookingCustomerBase
  - `[BookingCustomerId <String>]`: key: id of bookingCustomer
  - `[BookingServiceId <String>]`: key: id of bookingService
  - `[BookingStaffMemberBaseId <String>]`: key: id of bookingStaffMemberBase
  - `[BookingStaffMemberId <String>]`: key: id of bookingStaffMember

SCHEDULINGPOLICY <IMicrosoftGraphBookingSchedulingPolicy>: This type represents the set of policies that dictate how bookings can be created in a Booking Calendar.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AllowStaffSelection <Boolean?>]`: True if to allow customers to choose a specific person for the booking.
  - `[MaximumAdvance <TimeSpan?>]`: Maximum number of days in advance that a booking can be made. It follows the ISO 8601 format.
  - `[MinimumLeadTime <TimeSpan?>]`: The minimum amount of time before which bookings and cancellations must be made. It follows the ISO 8601 format.
  - `[SendConfirmationsToOwner <Boolean?>]`: True to notify the business via email when a booking is created or changed. Use the email address specified in the email property of the bookingBusiness entity for the business.
  - `[TimeSlotInterval <TimeSpan?>]`: Duration of each time slot, denoted in ISO 8601 format.

## RELATED LINKS

