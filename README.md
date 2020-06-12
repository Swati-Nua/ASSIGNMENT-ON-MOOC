# ASSIGNMENT-ON-MOOC && TOPIC: TUKEY'S TEST(POST HOC ANALYSIS)
# SUBMITTED BY SWATI KUMARI(MCA/10011/18) & ASTHA KUMARI(MCA/10004/18)

Tukey’s test is a single step multiple comparison process and statistical method. 
It is used to find means that are different from each other.

#import math as we need some variable,
- syfy integrate for F probability distribution function

-we are using decimal so our gamma function doesn’t blow up.

-csv is used so we can read in our data

-random is used to resample that data because working with 3 million data point isn’t practical.

-using function (t,z)  is a nested function. Here we define a constant e= euler’s number=2.71828. The reason we have done this is to handle some bigger numbers into the gamma function.

-using f_probability-distro_function is distribution function as well as a function to get p value by intergrating probability distribution function

-getP_from_f to get p value 

-getMean(sample) we have written to calculate mean 

-calculate_f () by passing factor

-order dict is a dictionary which maintains its order

- one_way_ANOVA is used to manage degree of freedom ,F- ratio
Here we have same exact differences ,f-distribution we have used dictionaries.
Return degree of freedom.

-now finally we move onto Tukey’s HSD
We have to do first the studentizeed range distribution . 
  snd_pdf()
  snd_cdf()
  srd_cdf_poly_two()
  srd_cdf()
  calculate_qs()
With all these done we are now ready to studentized range distribution, cumulative distribution . we take the integral of it to be able to get a p-value. This function will give p-value.
Mathematically same as above.

-make empty dictionary for all q’s 

-q is always going to be the positive difference between two means within a collection of means and that is always going to be divided by the standard error of those means.

-we now calculate q 

-tukeys_HSD() used which take two arguments 
We get q’s ang get groupsize ,no_of_grs,df
and perform calculations.

-we now perform one_Way_ANOVA.
Then if it significant we will do Tukey’s HSD  and result is declared; print them.

-Display other values .

-When we execute this we’ll see different results and its important to note that this is also a function of statistical power so it is likely to get a accurate result based on sample size used.
