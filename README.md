![WelcomeImage-Final](https://user-images.githubusercontent.com/84449238/188280316-d5655057-6511-4f02-ac8b-b33dabe7b59e.JPG)

# Predict_Turbine_Rotor_Bearing_Temperature-RenewPower-MachineHack

**1) Overview:-**

ReNew Power is one of the largest renewable energy Independent Power Producers in India and globally. ReNew Power develops, builds, owns, and operates utility-scale wind and solar energy projects, and hydro projects. As of June 14, 2022, ReNew Power had a gross total portfolio of ~12.8 GW of renewable energy projects across India. To know more, visit www.renewpower.in and follow us on LinkedIn, Facebook, Twitter and Instagram

Unplanned downtime of wind turbines can result in a significant loss of revenue and energy and can easily scale to millions of dollars a year. It is therefore pivotal that flagging of the failure of components is made to prevent further loss and perform maintenance. It, however, involves replacement of components and higher costs. Condition-based monitoring systems rely on supervisory control and data acquisition systems to predict faults and get valuable insights into the turbine’s performance.

In this hackathon, ReNew Power shared minute-wise normalised data of wind speed, power and temperature data for multiple components of a wind turbine. The company is looking to create a model to get an ideally functioning turbine’s expected rotor bearing temperature. It will then use the model to check the deviation of the actual rotor bearing temperature of the faulty turbine from the expected temperature. 

** It is to be noted that the hackathon is not a time series-based prediction, as data is divided randomly. 

**2) Dataset description:-** The dataset contains the following files,

**2.1) Train:-** 909604 rows x 16 columns 

![train_Data_P1](https://user-images.githubusercontent.com/84449238/188280798-ad081e6c-1b73-43c4-873a-c68c87c8654d.JPG)

![train_Data_P2](https://user-images.githubusercontent.com/84449238/188280954-becff177-877a-4bde-9878-1ad376c8d324.JPG)


**2.2) Test:-** 303202 rows x 14 columns

![Test_Data_P1](https://user-images.githubusercontent.com/84449238/188281174-00f20969-869a-40a3-ae93-6c75d98b8cfc.JPG)

![Test_Data_P2](https://user-images.githubusercontent.com/84449238/188281323-bc780142-8ec3-464a-8c93-8a39de20adad.JPG)

**3) Evaluation:-**

3.1) The submission will be evaluated using the Mean Absolute Percentage Error.

3.2) The public leaderboard is evaluated on 25% of Test data.

3.3) The private leaderboard will be made available at the end of the hackathon which will be evaluated on 100% of Test data.

3.4) Final score will be  70*[Leaderboard (100% of test dataset)] + 30*[Solution Approach/Code]

**4) Competition Link:-**  https://machinehack.com/hackathons/renew_power_hiring_hackathon/overview
