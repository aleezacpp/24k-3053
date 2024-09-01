START
Input N1
Input N2

store N1 under the variable T
REPEAT UNTIL
T%N2 == 0
END REPEAT
lcm=T
ELSE
T=T+N1
GCD=N1*N2/lcm
print GCD
