#TheHut

##Problem Statement

Amit has been frequenting Thalassery Hut for lunch since he has joined college. An issue he always faces is the unavailability of seats during peak lunch hours due to which he either has to spend a long time waiting or he has to eat somewhere else. Implement an efficient solution for Amit’s problem.

##The Solution

The purpose of this prototype is to propose and test a model which solves the waiting time delay in the Hut. This model will provide a framework for evaluating the impact of customer reaction to the wait experience.

Here the seats (availability) vs the person in queue (demand) if taken strictly , we cannot solve this by social and psychological solutions. Hence we need a queue management method.

So we have taken the virtual queueing system to take into the solution. It can be either a web, app, progressive web app etc (lets say Mobile App). A token consist of a #NUMBER and the TIME associated with it which can be set by the Hut manually considering the crowd for the time taken. Customer can take the time or token alloted from the App. Here the customer want to pay an initial amount(non-refundable) for getting token inorder not to duplicate the token, and will be deducted from the total amount.The offline customers should also get token by hand from the Hut if not taken online.

Hence we can provide the time alloted to them efficiently, and people can come or book at a convenient and available time.Thereby efficiently solving the customer satisfaction.

The prototype is given here above in three pictures. Kindly look it.