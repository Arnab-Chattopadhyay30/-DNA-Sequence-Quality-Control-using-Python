sequences = [
    "ATGCGTACGTA",
    "ATGCCGT",
    "GGCGCGCGCG",
    "ATXCGTAC",
    "ATATATATATAT",
    "GCGTACG",
    "",
    "ATGCGCATGCATGC"
]
for sequence in sequences :
      valid = True

      if sequence == "" :
          valid = False
      for bases in sequences :
          if bases != "A" and bases != "T" and bases != "G" and bases != "C" :
              valid= False
      if valid :
          print(sequence,"valid")
      else :
          print(sequence, "Invalid")

print("Length of the sequences ")

valid_count = 0

for sequence in sequences:
    if sequence == "":
        continue

    valid_count += 1

print("No of sequences:", valid_count)

print("Number of bases")
A=[]
T=[]
G=[]
C=[]

for sequence in sequences :
    print("Count of A:",sequence.count('A'))
    (A.append(sequence.count("A")))


for sequence in sequences:
    print("Count of T:", sequence.count('T'))
    (T.append(sequence.count("T")))


for sequence in sequences :
    print("Count of G:",sequence.count('G'))
    (G.append(sequence.count("G")))


for sequence in sequences :
    print("Count of C:",sequence.count('C'))
    (C.append(sequence.count("C")))


print("A",A)
print("T",T)
print("G",G)
print("C",C)

print("Total count of A :",sum(A))
print("Total count of G :",sum(G))
print("Total count of C : ",sum(C))
print("Total count of G : ",sum(T))


b = sum(A) + sum(T) + sum(G) + sum(C)
GC = (sum(G) + sum(C)) / b
print('%GC is ', GC)


print("=========================== QC Report =========================")

print("A",A)
print("T",T)
print("G",G)
print("C",C)

print("A",A)
print("T",T)
print("G",G)
print("C",C)


print("Total count of A :",sum(A))
print("Total count of G :",sum(G))
print("Total count of C : ",sum(C))
print("Total count of G : ",sum(T))

print('%GC is ', GC)
