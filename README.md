# This program gives quotient and remainder in eax and edx register respectively
INCLUDE Irvine 32.inc
.data
arr dword 2 dup(?)
.code
main PROC
mov eax,0
;User input 1st value
call readint
mov arr,eax
;User input 2nd value
call readint
mov arr+1,eax
mov eax,arr
mov edx,0
div arr+1
call writeint
mov eax,edx
call writeint
call readint
exit
main endP
end main
