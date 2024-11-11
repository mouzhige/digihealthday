# LLM

This README provides the steps to build a local LLM with google colab.
- Python (for `pip` commands)
- Node.js (for `npm` commands)

## Step 1
To install the necessary dependencies, run the following commands:

```bash
!pip install streamlit
!pip install ctransformers
!npm install localtunnel
```

## Step 2
create a file called app.py

```bash
%%writefile app.py
```

## Step 3
copy the file to from repo

```bash
%%writefile app.py
```

## Step 4
Download a LLM

```bash
!wget https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/resolve/main/llama-2-7b-chat.ggmlv3.q2_K.bin
```

## Step 5
Check your own IP

```bash
! wget -q -O - ipv4.icanhazip.com
```

## Step 6
Run and input your own IP

```bash
! streamlit run app.py & npx localtunnel --port 8501
```


