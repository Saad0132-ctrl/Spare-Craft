# Spare-Craft Maestro Tests

Mobile UI tests for Spare-Craft app using Maestro.

## Structure

```
.maestro/
├── config/
│   ├── main.yaml
│   └── env.yaml
└── flows/
    ├── auth/      # Registration & Login
    ├── buy/         # Shopping
    ├── send/        # Checkout
    └── transfer/    # Order completion
```

## Usage

```bash
maestro test .maestro/config/main.yaml
```

## Test Data

- Email: testing@gmail.com
- Password: Password123!
- Name: Testing SC