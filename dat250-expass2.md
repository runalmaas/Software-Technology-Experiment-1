
# Software Technology Experiment Assignment 2


## Technical problems

During the installation i found that working with terminals in windows can be very difficult. I had problems with the command
> set CLASSPATH

and

> set DERBY_INSTALL

as they didnt seem to work. I still have no idea how i fixed it because it just started working without me doing anything special. I also tried using the given scripts that was supposed to do this automatically, but they did not work either. 


## Database inspection

### Experiment-1

There was no problems connecting to the databse using the ```java org.apache.derby.tools.ij``` command and doing the steps like this:

![](https://scontent.fsvg2-1.fna.fbcdn.net/v/t1.15752-0/p280x280/118773055_1031352080619912_267030489629503377_n.png?_nc_cat=107&_nc_sid=b96e70&_nc_ohc=dPc-W-VDfM4AX8fgmkr&_nc_oc=AQlxb5y2zBwqwVMWguw-qu97UY8brMhlISLhv5x8LDwIUid5rpnTvZ0oz7MpgcwflX4&_nc_ht=scontent.fsvg2-1.fna&oh=eb6915140917954804ccf23469b257c6&oe=5F763594)

### Experiment-2

Doing the same as in [experiment-1](#experiment-1).

![](https://scontent.fsvg2-1.fna.fbcdn.net/v/t1.15752-0/p480x480/118700656_313089599768923_8076000796560856623_n.png?_nc_cat=108&_nc_sid=b96e70&_nc_ohc=KCB9ttHkmrUAX-nBxA7&_nc_ht=scontent.fsvg2-1.fna&oh=79df4eed8f2a78681b2c33756d33f34f&oe=5F73B6DA)

I had no initial answer to this exercise so i can't tell if they correspond with what I would have answered.

I implemented it using very basic code and the lombok library. A example output of the Person table using ```"select m from Person m"``` and automatic primary key generation would look like this:

![](https://scontent.fsvg2-1.fna.fbcdn.net/v/t1.15752-9/118763634_600996587254987_2231878769238934403_n.png?_nc_cat=110&_nc_sid=b96e70&_nc_ohc=HBp7vcWmrvQAX-gziVC&_nc_ht=scontent.fsvg2-1.fna&oh=9e3df44cb94c6e70ac5dc2b7940623b2&oe=5F74E877)

## Pending issues
While I tried to do the vogella tutorial I got a problem with Entity Managers. 

![](https://scontent.fsvg2-1.fna.fbcdn.net/v/t1.15752-9/118709590_692925054657296_318132931294852922_n.png?_nc_cat=100&_nc_sid=b96e70&_nc_ohc=Q6eboZn0hdoAX98iExv&_nc_ht=scontent.fsvg2-1.fna&oh=3c1c94e575ba03ecd17b40ff0971be9d&oe=5F7681D7)

This problem was first encountered while using the given maven skeleton, but after i did alot of cleaning in the filestructure it startet working(The error said 'No Persistence provider for EntityManager named todos'). This image was from when I tried to do the second part of the tutorial(the one with person, family, job). I could not get this to work a second time, so i just imported it to the working java project. To make it clear, I have no idea how I got it to work the first time, and when I got the same problem again it did not work no matter what I did.

Seems like you need a very specific file structure to get it working.



