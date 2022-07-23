# A-virtual-calculator
simple notepad program

1) Paste the following into a Notepad doc:
@echo off
title Batch Calculator by seJma
color 1f
:top
echo --------------------------------------------------------------
echo Welcome to Batch Calculator
echo --------------------------------------------------------------
echo.
set /p sum=
set /a ans=%sum%
echo.
echo = %ans%
echo --------------------------------------------------------------
pause
cls
echo Previous Answer: %ans%
goto top
pause
exit

2) Save as a .bat file.

3) Math away. Note: it can only handle integers. And only those of a certain number of digits. It also doesn't handle complex equations all that well. But other than all that, it's just fine.
