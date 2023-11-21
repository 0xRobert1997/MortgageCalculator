# MortgageCalculator

App is calculating and printing mortgage repayment schema using input data from inputData.csv file.

* User can define following parameters:
* RepaymentStartDate - starting date of repaying
* Wibor - interbank reference yield rate eg. 1.70
* Amount - total amount of mortgage
* MonthsDuration - total duration of mortgage
* InstallmentType - type of installment, eg. CONSTANT or DECREASING 
* Margin - percentage of margin
* OverpaymentProvision - provision that bank takes from overpaying
* OverpaymentProvisionMonths eg. 36 - if borrower overpay mortgage after 36 month, bank will not take provision
* OverpaymentStartMonth eg. 1 - month when borrower can start overpaying
* OverpaymentSchema - schema of months and values of overpayment eg. 2:10000,3:10000,5:10000,6:10000,7:10000
* OverpaymentReduceWay - overpaying can reduce period or reduce installment eg. REDUCE_PERIOD or REDUCE_INSTALLMENT
* MortgagePrintPayoffsSchedule eg. True - if user wants to print payoff schedule or False if not
* MortgageInstallmentNumberToPrint - number of installments to print

