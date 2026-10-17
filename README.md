# Growth Spurt Recognition

Building AI course project

## Summary

Growth spurts are a common factor for sports-related injuries in young athletes. This machine learning tool recognizes growth spurts using regular measurements and lets the athlete and coach know when to adjust training to minimize the risk of repetitive strain injuries.

## Background

As an experienced figure skating coach, I have seen many cases of growth spurts and strain-related injuries within athletes of 10-15 years of age. Sometimes the training is too hard or too unilateral during a growth spurt. Sometimes even the athletes themselves push too hard to reach their goals. Repetitive strain injuries might keep an athlete away from training for months or be a reason to stop training entirely. Growth spurts increase the risk of different injuries and could perhaps be quite easily recognized with the help of regular measuring and machine learning.

* **Problem 1:** Disciplines that include a lot of jumping load the body in a way that might cause Osgood-Schlatter or other similar-type repetitive strain injuries.
* **Problem 2:** In disciplines that require extreme flexibility, it is possible to stretch too hard and end up with an injury in a joint growth site.

## How is it used?

Athletes aged 10-16 get their height and back length measured once a month and insert their measurements into an app on their phones. When the app detects a growth spurt, it gives that information to the individual and maybe the coach as well, so they can check the workload or exercises to be more suitable for that phase of the athlete's development. Also, in the app, there would be other information such as the athlete's weight, age, training load, sport, and start of menstruation.

## Data sources and AI methods

The base data for this machine could possibly come from scientific research on growth spurt-related injuries, or possibly from clubs or coaches who might have collected suitable data already. Different sports have their own typical repetitive strain injuries, so many different sports and disciplines should be taken into account.

The AI would likely use anomaly detection or time-series analysis to spot sudden spikes in height and combine it with the training load data to predict injury risk. 

## Challenges

Growth spurt itself will be one of the easiest things to notice; it is quite simply just the measurements, age, and start of puberty to take into account. Training load, number of repetitions, or stretching too much are much more vague and thus harder to measure, and they are more up to coaches, physiotherapists, or doctors to decide what is too much. After all, the athlete wants to develop in skills and qualities and cutting too much from training is not great either. Also, privacy is an important question. Is it unethical for the coach to know when the athlete has her first period?

## What next?

What do I need to launch this app? Expertise from software developers, as I am not one. Maybe people from Suunto, Polar, or FitBit would be interested in a project like this. I think that after first working with data from young athletes and their injuries, this could grow into something that also helps adult athletes and actually anyone who exercises to avoid repetitive strain injuries.

## Acknowledgments

* Template and inspiration: Building AI course project by Reaktor Innovations and University of Helsinki.
* Based on personal coaching experience and sports injury research.
