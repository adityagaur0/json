```
"owners": {
  "owner_id_1": {
    "name": "Owner 1",
    "username": "owner1_username",
    "email": "owner1@example.com",
    "phone": "1234567890",
    "profilePhoto": "url_to_profile_photo"
  },
  // Add more owners as needed
},

"properties": {
  "property_id_1": {
    "propertyName": "Property 1",
    "address": "123 Main St",
    "city": "City 1",
    "pincode": "12345",
    "ownerId": "owner_id_1"
  },
  // Add more properties as needed
},

"floors": {
  "floor_id_1": {
    "floorNumber": 1,
    "propertyId": "property_id_1"
  },
  // Add more floors as needed
},

"units": {
  "unit_id_1": {
    "unitNumber": "001",
    "floorId": "floor_id_1"
  },
  // Add more units as needed
},

"tenants": {
  "tenant_id_1": {
    "name": "Tenant 1",
    "phone": "9876543210",
    "propertyId": "property_id_1",
    "floorId": "floor_id_1",
    "unitId": "unit_id_1",
    "moveInDate": "2024-01-24",
    "rentAmount": 1000,
    "depositAmount": 500,
    "rentRenewalDate": "2024-02-24",
    "paymentStatus": true,
    "paidCurrentMonth": false,
    "paidDeposit": true,
    "status": "Occupying"
  },
  // Add more tenants as needed
},

"dues": {
  "due_id_1": {
    "tenantId": "tenant_id_1",
    "propertyId": "property_id_1",
    "dueType": "Monthly Rent",
    "amount": 100,
    "dueStartDate": "2024-01-01",
    "description": "January 2024 Rent"
  },
  // Add more dues as needed
},

"payments": {
  "payment_id_1": {
    "tenantId": "tenant_id_1",
    "propertyId": "property_id_1",
    "amount": 90,
    "dueId": "due_id_1",
    "paymentDate": "2024-02-01",
    "paymentMode": "Cash",
    "adjustFromDeposit": false
  },
  // Add more payments as needed
},

"deductions": {
  "deduction_id_1": {
    "tenantId": "tenant_id_1",
    "propertyId": "property_id_1",
    "amount": 10,
    "deductionDate": "2024-02-01",
    "description": "Deducted from security deposit"
  },
  // Add more deductions as needed
}

```
