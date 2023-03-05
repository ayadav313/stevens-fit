# Stevens Fit

Team Members: Abhishek Yadav, Angelo Saez, Yousef Khalil, George Sheng

## Pitch

Are you tired of trying to navigate the UCC gym on your own? Do you struggle to create effective workout plans that cater to your specific fitness goals? Look no further! Our team is excited to introduce a new fitness app that will revolutionize the way you work out on campus.

Introducing "Stevens Fit" - the ultimate fitness app designed specifically for Stevens students. Our app offers customized workout plans and fitness challenges that are tailored to the equipment available at the UCC gym. With Stevens Fit, you will no longer need to aimlessly wander around the gym trying to figure out what to do next.

Stevens Fit offers a range of features that are designed to help you achieve your fitness goals, including the ability to track your sets, reps, and weight. You can also track your food intake to ensure you're fueling your body with the right nutrients to power through your workouts.

But that's not all! With Stevens Fit, you can plan workouts ahead of time to ensure you're making the most of your time at the gym. You can even plan your workouts around your class schedule to ensure you're staying on track with your fitness goals.

One of the most exciting features of Stevens Fit is the ability to connect with your gym buddies. You can use location tracking to send notifications to your friends list when you're headed to the gym, or use a button to notify your gym friends that you're looking for a spotter. With Stevens Fit, you'll never have to work out alone again!

Our team is passionate about helping Stevens students achieve their fitness goals. We believe that Stevens Fit has the potential to change the way students approach fitness on campus. With your support, we can bring this exciting new app to life and help students achieve their fitness goals.

## Requirements

- A user login system.
  - create acct and login via Stevens.edu email
- AJAX form submissions and error checking.
- Data-related code organized in modules.
- Use of a MongoDB Database.
- Basic defense against XSS attacks.
- Use of client-side JavaScript
- All error handling
- You will need to validate your user’s input in 3 places. On the client-side (to avoid unnecessary requests to the server), in your routes and in your DB functions.

## Core features

- Exercise catalog: DB with exercises users can select to see more information. When users go to track workouts, follow pre built workouts, or make their own custom workouts: They will be able to select the exercises from a nice UI menu. I.e. I should see "Bench press", "Squat" and a generic picture of that exercise.
  - YT video explanation
  - Users history with that exercise. For example, show a graph of all my weights on the bench press. 
  - Some fun stats like all time set or rep numbers for the exercise. 
- Tracker: Track exercises, sets, reps, weights per workout
- Tracker: Save workout at the end of the session
- Tracker: Graphs, stats, etc using user inputed data
- Workout catalog: Gives workouts tailored to UCC Gym
- Workout catalog: Create your own custom workouts and be able to save these workouts

## Extra features

- Social platform
  - Be able to add friends and see their progress towards their fitness goals.
  - Coordinate workouts with friends and find workout partners or spotters.
  - Notify your friends when you're at the gym and see who else is working out at the same time.
- Calendar: Put workouts in a calendar and send notifications for reminders
- Calendar: Import class schedule to plan workouts around
- Track food intake and provide recommendations for healthy meals based on the user's fitness goals. The app can have a food item database with options from Stevens Dining Hall as well as local popular food places.
