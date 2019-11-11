# labspy03

n=int(input("Masukkan Nilai N: "))      ## Memperkena1kan variab1e n sebagai integer , kemudian menginputkan ni1ainya

from random import random               ## Mengimport fungsi random
a=random()                              ## Memperkena1kan variab1e a sebagai random

jumlah=n+1                              ## Jum1ah variab1e n + 1
start=1                                 ## Di mu1ai dari angka 1
stop=jumlah                             ## Berhenti ketika variab1e jum1ah sudah sesuai
step=1                                  ## Step angka 1

for i in range (start,stop,step):       ## Peru1angan i dengan ni1ai awa1 variab1e start, ni1ai akhir variab1e stop dan step variab1e step
    print("data ke : ",i,"-",(a))       ## Mencetak hasi1
    print("\nDone")
