# Streamlit Basic Components

Welcome to this blog post about the basic components of Streamlit, a powerful tool for creating interactive web applications with Python. This guide will introduce you to some of the essential components you can use to build your own Streamlit apps.

## Table of Contents
1. [Introduction](#introduction)
2. [Text Elements](#text-elements)
3. [Data Display Elements](#data-display-elements)
4. [Input Widgets](#input-widgets)
5. [Media Elements](#media-elements)
6. [Layout and Control](#layout-and-control)
7. [Conclusion](#conclusion)

---

## Introduction
Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes, you can build and deploy powerful data apps.

---

## Text Elements
Streamlit offers several functions to display text in your app. Here are some of the basic ones:

| Function | Description | Example |
| -------- | ----------- | ------- |
| `st.title` | Displays a title | `st.title('This is a title')` |
| `st.header` | Displays a header | `st.header('This is a header')` |
| `st.subheader` | Displays a subheader | `st.subheader('This is a subheader')` |
| `st.text` | Displays fixed-width text | `st.text('This is some text')` |
| `st.markdown` | Displays markdown-formatted text | `st.markdown('**This is bold text**')` |
| `st.latex` | Displays mathematical expressions formatted in LaTeX | `st.latex(r'E = mc^2')` |
| `st.code` | Displays a block of code | `st.code('print("Hello, Streamlit!")', language='python')` |

---

## Data Display Elements
Streamlit provides several ways to display data, including tables and charts:

| Function | Description | Example |
| -------- | ----------- | ------- |
| `st.dataframe` | Displays a data frame as an interactive table | `st.dataframe(my_dataframe)` |
| `st.table` | Displays a static table | `st.table(my_dataframe)` |
| `st.line_chart` | Displays a line chart | `st.line_chart(data)` |
| `st.bar_chart` | Displays a bar chart | `st.bar_chart(data)` |
| `st.map` | Displays a map | `st.map(data)` |

---

## Input Widgets
Input widgets allow you to capture user input in your Streamlit app:

| Function | Description | Example |
| -------- | ----------- | ------- |
| `st.button` | Displays a button | `if st.button('Click me'): st.write('Button clicked!')` |
| `st.slider` | Displays a slider | `age = st.slider('Select your age', 0, 100, 25)` |
| `st.text_input` | Displays a text input box | `name = st.text_input('Enter your name')` |
| `st.text_area` | Displays a text area | `bio = st.text_area('Enter your bio')` |
| `st.selectbox` | Displays a select box | `option = st.selectbox('Choose one', ['Option 1', 'Option 2', 'Option 3'])` |
| `st.multiselect` | Displays a multi-select box | `options = st.multiselect('Choose one or more', ['Option 1', 'Option 2', 'Option 3'])` |
| `st.checkbox` | Displays a checkbox | `agree = st.checkbox('I agree')` |
| `st.radio` | Displays a set of radio buttons | `choice = st.radio('Choose one', ['Option A', 'Option B', 'Option C'])` |

---

## Media Elements
Streamlit allows you to display media like images, audio, and video:

| Function | Description | Example |
| -------- | ----------- | ------- |
| `st.image` | Displays an image | `st.image('path/to/image.png')` |
| `st.audio` | Plays an audio file | `st.audio('path/to/audio.mp3')` |
| `st.video` | Plays a video file | `st.video('path/to/video.mp4')` |

---

## Layout and Control
Streamlit offers various elements to manage the layout and flow of your app:

| Function | Description | Example |
| -------- | ----------- | ------- |
| `st.sidebar` | Creates a sidebar for additional input widgets | `st.sidebar.selectbox('Choose one', ['Option 1', 'Option 2'])` |
| `st.columns` | Creates a multi-column layout | `col1, col2 = st.columns(2)` |
| `st.expander` | Creates an expandable/collapsible section | `with st.expander('Expand me'): st.write('Hidden text')` |

---

## Conclusion
This blog post covered the basic components of Streamlit, which you can use to create interactive and user-friendly web applications. Explore these components to enhance your data apps and make them more engaging.

Happy Streamlit-ing!

---

Feel free to contribute to this repository or ask questions if you need any further assistance.

---
