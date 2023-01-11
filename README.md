# AWS SDK

Lambdas:

- create-client: load clients with ID, name, surname and date of birth. You should only allow adults up to 65 years of age
- create-card: grants a credit card (Classic if under 45 and Gold if older) generating number, expiration date and security code.
- create-gift: assign a birthday gift according to the season in which it falls, varying between a sweatshirt if it is autumn, a sweater if it is winter, a shirt if it is spring and a t-shirt if it is summer.

## Body

Required fields for create-client:

```javascript
{
    "dni":"0303456",
    "name": "Pepe",
    "lastName": "Argento",
    "birth": "1992-06-09"
}
```

Required fields for create-card:

```javascript
{
    "dni":"0303456"
}
```

Required fields for create-gift:

```javascript
{
    "dni":"0303456"
}
```
