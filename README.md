# python-data-structure-Average-spam-confidence-
7.2 Assignment
fname =raw_input("Enter file name: ")
fh = open(fname)
re=0
l=0
for line in fh.roadlines():
    if ine.startswith("X-DSPAM-Confidence:"): 
		    line.replace(" ","")
        ind=line.find(":")
        l=1+1
        re=re+(float(line[ind+1:]))
        print("Average spam confidence:",re/l)
