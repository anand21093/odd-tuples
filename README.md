# odd-tuples
#Write a procedure called oddTuples, which takes a tuple as input, and returns a new tuple as output, where every other
#element of the input tuple is copied, starting with the first one. So if test is the tuple ('I', 'am', 'a', 'test', 'tuple'),
#then evaluating oddTuples on this input would return the tuple ('I', 'a', 'tuple').

def oddTuples(aTup):
    newTup = aTup[::2]
    return newTup

#TestCode
print (oddTuples((20, 19, 4, 7, 19, 5, 12, 9)))
print (oddTuples((8, 3, 17, 3, 9, 1)))
print (oddTuples((18, 0, 3, 9, 12, 14, 10, 13)))
