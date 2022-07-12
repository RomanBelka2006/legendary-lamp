# legendary-lamp
Calculator
@echo off
title Calculator
Color f1
:start
echo ---------------------------------
echo Welcome to the Calculator
echo ---------------------------------
echo.
set /p sum=Please enter the question:
echo.
set /a ans= %sum%
echo.
echo The Answer = %ans%
echo.
echo ______________________
pause
cls
echo Previous Answer = %ans%
echo.
goto start
exit
