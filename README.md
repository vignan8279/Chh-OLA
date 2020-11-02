# Chh-OLA

## Estimate the total fare amount of trip prior to the booking using various trip parameters.

### train.csv contains the training set data, test.csv contains the test set data.
### main.ipynb contains my model.

# DataSet

The data contains information about 1.4 million trips in Chh-OLA cabs, in the form of 17 columns, each having specific information about the respective trip.

ID - Unique Identifier.

vendor_id - Taxi data providing vendor; 1 = TaxiTech Inc. 2 = DataCollectors Inc.

pickup_loc - Location ID from where passenger was picked up.

drop_loc - Location ID where passenger was dropped.

driver_tip - Tip given to driver.

mta_tax - Automatically triggered tax amount.

distance - Distance covered in the trip.

pickup_time - Date/Time when meter started.

drop_time - Date/Time when meter stopped.

num_passengers - Cab passenger count.

toll_Amt - Toll paid in the booths.

payment_Method - Method of payment symbolised by a numeric code (1 = Credit Card, 2 = Cash, 3 = Free ride, 4 = Disputed, 5 = Unknown, 6 = Void trip).

rate_code - Rate code for the trip (1 = Standard, 2 = Airport, 3 = Connaught Place, 4 = Noida, 5 = Negotiated Fare, 6 = Pooled ride).

stored_flag - Flag which signifies whether trip data was immediately sent to Chh-OLA’s database or not (Y=Yes, N=No, because of connection error).

extra_charges - Miscellaneous charges.

improvement_charge - Charge levied for improvement in infrastructure.

total_amount - Output label; Final amount to be paid including meter fare and all extra charges.



