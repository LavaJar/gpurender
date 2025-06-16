import streamlit as st

st.title("Talk to the App!")

user_input = st.text_input("Say something:")

if user_input:
    st.write(f"You said: {user_input}")
