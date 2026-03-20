# Payment Flow

## Step-by-Step Flow

1. user initiates payment
2. request enters API layer
3. authentication and validation
4. balance check via core
5. compliance and cutoff validation
6. fraud checks applied
7. instruction generated
8. sent to processor
9. status updates received
10. transaction finalized

---

## Key Insight

All validation happens before sending instructions downstream.
