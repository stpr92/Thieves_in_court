from pprobs.simulation import Simulator 

simulator=Simulator()

simulator.add_event('G',0.88)  # "G" as Giulty
simulator.add_event('I',0.12)  # "I" as Innocent
simulator.add_event('C|G',0.74)  # "C" as Criminal (after being convicted in court)
simulator.add_event('C|I',0.06)  # criminal in case of being innocent

x=simulator.get_prob('G|C')  # probability of being giulty in case of being criminal
print(x)

#result will be : 0.9891
