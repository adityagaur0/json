# json  

```
{
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
      // Add more property details as needed
    },
    // Add more properties as needed
  },

  "floors": {
    "floor_id_1": {
      "floorNumber": 1,
      "propertyId": "property_id_1"
      // Add more floor details as needed
    },
    // Add more floors as needed
  },

  "tenants": {
    "tenant_id_1": {
      "name": "Tenant 1",
      "phone": "9876543210",
      "propertyId": "property_id_1",
      "floorId": "floor_id_1",
      "moveInDate": "2024-01-24",
      "rentAmount": 1000,
      "depositAmount": 500,
      "rentRenewalDate": "2024-02-24",
      "paymentStatus": true
      // Add more tenant details as needed
    },
    // Add more tenants as needed
  },

  "dues": {
    "due_id_1": {
      "tenantId": "tenant_id_1",
      "propertyId": "property_id_1",
      "dueType": "Rent",
      "amount": 200,
      "dueStartDate": "2024-01-01",
      "description": "Monthly rent"
      // Add more due details as needed
    },
    // Add more dues as needed
  },

  "payments": {
    "payment_id_1": {
      "tenantId": "tenant_id_1",
      "propertyId": "property_id_1",
      "amount": 200,
      "dueDate": "2024-01-15",
      "collectedAmount": 200,
      "collectionDate": "2024-01-15",
      "collectionMode": "Cash",
      "adjustFromDeposit": false
      // Add more payment details as needed
    },
    // Add more payments as needed
  }
}

```
