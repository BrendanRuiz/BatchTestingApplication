Testing capability for SARS-CoV-2, the virus that causes Covid-19 infection, is extremely limited in the United States and in most countries. Testing involves swabbing the nose (and/or throat) and looking for the presence of viral RNA. There are shortages of viral transport medium (the liquid in which the swab is placed), swabs, and machines to do the test. The main shortage is the machines that run the tests. That’s why optimization is needed in the testing process.
 
This is the usual way testing is done. The sample sent to the lab from each person consists of a little swab in a tube with viral transport medium. The lab shakes up the tube and draws out 300 microliters of fluid to put into the machine to test for the presence of virus. There is enough fluid left over in the tube to perform one additional test if needed.
 
One proposed solution to insufficient testing capacity is batch testing. That means combining samples from 10 or so people and running the test on the combined viral transport medium from all 10 people. If the batch test is negative, no one in that group has the infection. If the test is positive, then subsequent tests are needed to find out the person, or persons, in that batch who are positive. The reason why we should not batch more than 10 people is that the virus gets diluted if only one person in the batch is positive. A dilution of 10:1 is the most we can safely dilute and still detect virus. Remember, you can only run 2 tests on any sample you receive. And it’s not practical to go back to the person and swab them again!
 
 Why would people be tested if they have no symptoms? Because they might need testing to go back to school, or for their jobs, or because they were exposed to someone with Covid-19, or because they are scheduled for elective surgery or elective procedures.
 
 
Imagine a situation where you have a batch of 10 patients, and no one in the batch has the infection. Then you can get results for 10 people by running one test. That really speeds things up. What if 1 person out of the 10 is positive? Then the batch will test positive, but you must run an additional 10 tests, one on each patient, to see who is positive and who is negative. In that scenario batch testing is wasteful because you had to run 11 tests instead of 10. Testing is optimized when people with the lowest risk of infection are batched. Above a certain probability of infection, batching is wasteful. I don’t know enough probability to tell you when to stop batching and to run only individual tests, but I bet you could figure that out.  Whenever the batch is negative, you have saved 9 tests. Whenever the batch is positive, you’ve wasted 1 test. This is compared to regular individual testing.
 
So, the app must look at the collection of samples from patients and determine which ones, if any, to batch.
 
Think about whether you should ever use smaller batch sizes. Never use sizes larger than 10 since that will make the results less reliable (more false negatives). The ideal solution tells you how many tests you save when you batch a group of people with specific pretest probabilities of having Covid-19.


TODO: Features to add 
1. Change med record numbers
2. Change areas to numbers
3. Move data to seperate TS file
4. Add weights to COVID score
5. Add test simulator that randomly decides if batch is positive or negative
6. Add more data/read in data from csv