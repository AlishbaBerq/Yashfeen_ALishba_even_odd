import streamlit as st

def check_even_odd(number):
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"

def main():
    st.title("Even-Odd Checker")
    number = st.number_input("Enter a number:")
    
    if st.button("Check"):
        result = check_even_odd(number)
        st.write(f"The number {number} is {result}.")

if __name__ == "__main__":
    main()
