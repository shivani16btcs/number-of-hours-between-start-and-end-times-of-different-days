# number-of-hours-between-start-and-end-times-of-different-days
How to find the number of hours between start and end times of different days :  
*Given start-time: 17:25 dayCount: 1
end-time : 19:35 dayCount: 2 *  Output 26: 10 hrs




    let daycount = end.dayCount - start.dayCount;
    let startDate = '24/11/2021'.split('/');
    let enddate = +elDate[0] + +daycount
    let oldDate = elDate[1]+'/'+ elDate[0] +'/'+elDate[2]      //   11/24/2021   
    let newDate = elDate[1]+'/'+ date +'/'+elDate[2];          //   11/25/2021  
    let timeStart = new Date(oldDate+" "+ start-time);
    let timeEnd = new Date(newDate+" "+ end-time);
    let diff =(timeStart.getTime() - timeEnd.getTime()) / 1000;
    diff /= 60;
    let minReach= Math.abs(Math.round(diff));
    let hourReach = (this.minReach / 60 ).toFixed(0);
    
    
    # count number of days spend together 
 
    leetcode: https://leetcode.com/contest/biweekly-contest-87/problems/count-days-spent-together/

