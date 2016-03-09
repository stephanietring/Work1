# Work1
#A. match_ends:Given a list of strings, return the count of the number of strings where the string length is 2 
#or more and the first and last chars of the string are the same.

#Note: python does not have a ++ operator, but += works.
def match_ends(words):
    i=0
    j=0
    while i  <= len(words)-1:
        if len(words[i])>=2 and words[i][0]==words[i][-1]:
             j+=1
        i+=1
    return j
