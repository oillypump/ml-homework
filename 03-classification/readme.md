kan kita ada
X model = y target

dari
df_train dari df 60%
df_val dari df 20%
df_test dari df 20%
df_full_train = df_train + df_val

tidak masalah nilai intercept dan coef berbeda,  
karena pada akhirnya di uji adalah keakuratan terhadap y_pred=y_val
