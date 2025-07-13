# Code Review Assistant

**Category**: Technical  
**Tags**: [#code-review, #programming, #debugging, #best-practices, #refactoring]

---

## 🧭 Purpose
Conduct thorough code reviews that improve code quality, catch bugs, and ensure adherence to best practices and design patterns.

---

## 🧠 Prompt Template
Act as a senior [language] developer with expertise in [frameworks/domains]. Review this code and provide feedback on:

1. **Bugs & Logic Errors**: Identify any potential issues
2. **Performance**: Suggest optimizations where applicable
3. **Security**: Flag any vulnerabilities or unsafe practices
4. **Readability**: Improve naming, structure, and documentation
5. **Best Practices**: Ensure adherence to [language] conventions and SOLID principles
6. **Edge Cases**: Identify unhandled scenarios

Code to review:
```[language]
[paste code here]
```

Prioritize feedback by severity (Critical/High/Medium/Low) and provide specific suggestions or code examples for improvements.

---

## 🧪 Example Prompt
> "Act as a senior Python developer with expertise in FastAPI and async programming. Review this code and provide feedback on bugs, performance, security, readability, best practices, and edge cases:
> 
> ```python
> async def get_user_data(user_id):
>     user = db.query(f"SELECT * FROM users WHERE id = {user_id}")
>     if user:
>         return {"user": user, "token": generate_token()}
>     return None
> ```
> 
> Prioritize feedback by severity and provide specific improvements."

---

## 💡 Tips for Use
- Include the specific context (API endpoint, library function, etc.)
- Mention any specific standards or style guides to follow
- Ask for refactored code examples for complex improvements
- Use for learning by asking "Explain why X is better than Y"

---

## 🔁 Variants
- **Security Focus**: "Perform a security-focused review, especially for [OWASP Top 10]"
- **Performance Audit**: "Focus on performance bottlenecks and optimization opportunities"
- **Junior-Friendly**: "Review as if mentoring a junior developer, with detailed explanations"
- **Architecture Review**: "Evaluate the design patterns and overall architecture"