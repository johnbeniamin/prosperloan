# prosperloan
### First, I want to introduce the dataset Iam working onز
the database is about the prosper loans system, its composed of 113937 notices of 81 variables
firs I chosse the variables I want to work on wich was 'LoanOriginalAmount', 'BorrowerAPR', 'StatedMonthlyIncome', 'Term', 'ProsperRating (Alpha)', 
        'EmploymentStatus', 'MonthlyLoanPayment','Investors', 'Occupation', 'CreditGrade','EmploymentStatusDuration','LoanStatus','BorrowerRate'
then I categeorised two groups as numerical and categorial variables as follows
num_vars = ['LoanOriginalAmount', 'BorrowerAPR', 'StatedMonthlyIncome','Investors', 'Term']
cat_vars = ['Term', 'ProsperRating (Alpha)', 'EmploymentStatus', 'CreditGrade']
Then I started to analyse the data in three steps, univariate, bivariate and multivariate exploration
I found many relations between variables:
- monthly income distribution is right skewed as the more the person has income the little he want to take a loan
- loans are taken more by employed persons rather then selfemployed
- opened poans which are being payed are more than all tha loans in the past even completed or cancelled
- I noticed some strong corelations between investors & loan amount, term& loan amount. this may need further invistigation
we find that the relation ship between loan amount and oan term increases as the APR increases, which mean as the trust in the customer increase you can lend him more money for more time to pay
