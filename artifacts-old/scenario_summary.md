### Scenario Metrics (Main Results)

| Scenario | Accuracy | P_good | R_good | F1_good | P_bad | R_bad | F1_bad | Features | Sensitive Mode |
|---|---:|---:|---:|---:|---:|---:|---:|---|---|
| all_features | 0.670 | 0.646 | 0.750 | 0.694 | 0.702 | 0.589 | 0.641 | Age, Sex, Job, Housing, Saving accounts, Checking account, Credit amount, Duration, Purpose | data_driven |
| financial | 0.624 | 0.609 | 0.693 | 0.648 | 0.644 | 0.555 | 0.596 | Saving accounts, Checking account, Credit amount, Duration, Purpose | ignore |
| personal | 0.532 | 0.518 | 0.939 | 0.668 | 0.673 | 0.125 | 0.211 | Age, Sex, Job, Housing | data_driven |