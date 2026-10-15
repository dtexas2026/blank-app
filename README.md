
import streamlit as st

st.set_page_config(
    page_title="AutoTech Navigator",
    page_icon="🚗"
)

st.title("🚗 AutoTech Navigator")
st.subheader("Capital One Auto Finance Training Demo")

employee = st.text_input("Employee Name")

st.write("Weekly Training Progress")
st.progress(0.50)

st.image(
    "https://images.unsplash.com/photo-1493238792000-8113da705763",
    caption="Automotive Training"
)

if st.button("Start Training"):
    st.success(f"Welcome, {employee}!")

