# Race-Day
let raceNumber = Math.floor(Math.random() * 1000);
let registeredEarly = true;
let runnerAge = 19;
 
if (runnerAge > 18 && registeredEarly) {
  raceNumber += 1000;
}
if (runnerAge > 18 && registeredEarly) {
  console.log(`Race time is at 9:30am. Your race number is ${raceNumber}.`);
}
else if (runnerAge >18 && !registeredEarly) {
  console.log(`Late adults run at 11:00 am. Your race number is ${raceNumber}.`);
}
else {
  console.log('See the registration desk.');
}
if (runnerAge < 18) {
  console.log('Youth registrants run at 12:30 pm (regardless of registration). Your race number is ${raceNumber}.');
}
 
