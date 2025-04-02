# **Black-Scholes Option Pricing Model in Python** 📈  

This project implements the **Black-Scholes option pricing model** to calculate the fair price of European call and put options.  

✅ **Quick to implement (~1 hour)**  
✅ **Great for resume & interviews**  
✅ **Demonstrates Python & Quantitative Finance skills**  

---

## **📌 Project Overview**  
The **Black-Scholes model** is a widely used mathematical model for pricing European options. It calculates the theoretical price of an option based on:  
- Current stock price ($S$)  
- Strike price ($K$)  
- Time to expiration ($T$)  
- Risk-free interest rate ($r$)  
- Volatility ($\sigma$)  

The model uses the following formula:  
\[
C = S N(d_1) - K e^{-rT} N(d_2)
\]
\[
P = K e^{-rT} N(-d_2) - S N(-d_1)
\]
where  
\[
d_1 = \frac{\ln(S/K) + (r + 0.5 \sigma^2) T}{\sigma \sqrt{T}}
\]
\[
d_2 = d_1 - \sigma \sqrt{T}
\]

---

## **📂 Project Structure**
