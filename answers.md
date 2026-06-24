About Me

1) Hi, I am Sujoy P T, a Data Science postgraduate from the University of Kerala with a strong mathematical foundation (B.Sc. in Mathematics). I am UGC NET qualified and specialize in developing intelligent, data-driven applications.  My hands-on experience spans across Machine Learning, Deep Learning, Computer Vision, and Generative AI. Some of my key projects include developing an underwater waste detection pipeline using YOLOv11, building an interactive RAG-driven AI Tutor Chatbot with FastAPI and React, and fine-tuning BERT models for NLP tasks. I enjoy writing clean code, solving algorithmic problems, and collaborating on building functional, real-world tech solutions.

2) Yes, I own and use a personal laptop for all my development, model training, and open-source contributions.

3) Operating System: Windows 11 , IDE / Editor: Visual Studio Code (VS Code) for general scripting, backend development (FastAPI), and web components,  Version Control & Config Management: Git and GitHub for version control, repository tracking, and collaboration. Environment management is handled via conda or venv to keep project dependencies isolated and clean.  

Social Profile

1) GitHub: https://github.com/Sujo04.  Portfolio: https://sujoy-portfolio.vercel.app/

The Real Stuff

1) Python and SQL

2) def digitize(num):
    return [int(digit) for digit in str(abs(num))]
   print(digitize(12345))
   
3) def remove_duplicates(arr):
    return list(set(arr))
   print(remove_duplicates([1, 2, 2, 3, 4, 4, 5]))

4) Need to work on this
5) def reverse(arr, start, end):
    while start < end:
        arr[start], arr[end] = arr[end], arr[start]
        start += 1
        end -= 1

   def rotate_left(arr, k):
    if not arr:
        return arr
        
    n = len(arr)
    k = k % n

    reverse(arr, 0, k - 1)
    reverse(arr, k, n - 1)
    reverse(arr, 0, n - 1)
    return arr
  my_list = [1, 2, 3, 4, 5, 6]
  print(rotate_left(my_list, 2)) 
