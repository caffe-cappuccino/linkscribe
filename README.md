# ✨ linkscribe  

👩‍💻 Built by a girl who codes (and sometimes overthinks captions).  
linkscribe is your **AI-powered LinkedIn post bestie** — turning your random thoughts into ✨professional✨ posts in seconds.  

---

## 💖 Why tho?  
Because...  
- LinkedIn posts shouldn’t feel like exams 🙃  
- Writer’s block is real (trust me, I know)  
- We deserve content that sounds *smart + authentic* without spending 2 hours on it  

---

## ⚡ Quick Start  

```bash
# clone me
git clone https://github.com/caffe-cappuccino/linkscribe.git
cd linkscribe

# install things
pip install -r requirements.txt

# run me 💫
python main.py --prompt "Your idea here" --tone "casual"
````

---

## 🛠️ Inside the magic

* `few_shot.py` → lil’ training examples for the AI
* `llm_helper.py` → the talk-to-AI hotline
* `post_generator.py` → the brain (aka main code)
* `preprocess.py` → cleans up messy stuff
* `main.py` → where it all begins

---

## 🎀 Example

```python
from post_generator import PostGenerator

gen = PostGenerator(api_key="YOUR_KEY")
post = gen.generate_post(
    prompt="Just finished building my first AI project 👩‍💻✨",
    tone="proud",
    style="short"
)
print(post)
```

---

## 🌸 Use it when...

* you wanna announce projects without sounding boring
* you’re flexing career milestones 🏆
* you wanna share learnings / thoughts but don’t know how to word it
* or just wanna look ✨put-together✨ on LinkedIn

---

## 🤝 Contribute

Pull requests are basically love letters 💌
So yeah… fork → build → PR.

---

## 📜 License

MIT — free, open, and girl-coded 💕

---


