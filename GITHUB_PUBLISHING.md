# GitHub publishing commands

Run these commands from the project folder after creating a new public repository on GitHub.

```bash
git init
git add Hotel_Booking_Demand_EDA.ipynb README.md requirements.txt
git commit -m "Add hotel booking demand EDA project"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/hotel-booking-demand-eda.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. Do not add the CSV unless its licence permits redistribution.
