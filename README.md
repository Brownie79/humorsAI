# Humors AI

## Description
The Humors AI is built to serve as a simulation of a human. The "brain" is composed of various 'humors' which request actions to fulfil thier 'happiness'. Failing to make them happy result in various chemical imbalances in your system, leading to sickness and death (Simulation End).

## Humors
Humors request the GetActions() script to fetch actions of type X that they need to make them 'happy' and fix chemical imbalances that are effecting them. 

They then score these actions through Happiness + Chemical Imbalance Cured - Chemical Imbalance Added and sends the list to the scheduler.

Each humor/temperment has 'needs' and 'wants' which help fulfill it's goals. There is a basic set of needs for each humor which need to be filled every x minutes. Wants are generated by actions available and if not fulfilled add unhappiness. Most wants are built from some sort of need. 

An action may fulfil mutiple needs/wants from multiple temperments. In which case the scheduler will give weigh it higher because of all the things it fulfils and it's more likely to be scheduled. 

+ Sanguine: Enthusiastic, Active, Social
    - Types of Needs:  Socializing, Excercise 
    - Types of Wants: 
+ Choleric: Short-Tempered, Fast, Irritable
    - Types of Needs:  Eating, Sleeping, 
    - Types of Wants:  
+ Melancholic: Analytical, Wise, Quiet
    - Types of Needs:  Thinking, Create Something
    - Types of Wants:  
+ Phlegmatic: Relaxed, Peaceful
    - Types of Needs:  Sleeping  
    - Types of Wants:

## Actions


## Scheduler
### Time:
A turn is considered 1 day split into 1440 minutes


## Chemical Balance
    