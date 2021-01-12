# What's this?

The project is about some data analysis on a dataset that contains over 100000 hospital appointments in Brazil.
In this project,  I'll be trying to answer the question of what's the reason behind some people not showing up to their appointments.
I'll be asking questions of my own in hopes of finding an answer to the big question.

# what kind of questions?

Well, the dataset contains a few important columns like:

1. Handcap: 1 if the patient is handycapped, 0 if not.
2. Age: The patient's age.
3. AppointmentDay: The date of the patient's appointment.
4. Scholarship: 1 if the patient is enrolled in the Brazilian health care program, 0 if not.
5. SMS_received: 1 if the patient has received an SMS telling them of their appointment, 0 if not.
6. No-show: 1 if the patient didn't show up to their appointment, 0 if they did. Those aren't all 

I used those columns from the dataset to ask questions like:

1. How many people did show to their appointments? and how many didn't?
2. How many people from those who didn't show up are enrolled in Brazilian health program?
3. How many people weren't in the Brazilian health program and didn't get an SMS?
4. How many of the people who didn't show up actually got an SMS?

and more.

# Conclusion

The answer I arrived to was that if a patient wasn't enrolled in the health program and didn't get an sms they have a big chance of not showing up to the appointment. I confess I really need more info that's not in the dataset to push my investigation further, but as far as the info in the dataset go, I think this is a really satisfying answer in my book.
There are actually a few more reasons, not just this one, please take a look at the notebook for more info.