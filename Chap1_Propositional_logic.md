# Propositional logic (logic mệnh đề)
  - target-of-logic in computer-science is to develop language to model the situation we encounter as computer-science-professional
  in such way that we can reason about them formally.
  (<ins>mục đích của logic trong KHMT</ins> là <ins>phát triển 1 ngôn ngữ</ins>  để <ins>mô hình hoá các tình huống</ins>,
  dựa vào (ngôn ngữ) đó chúng ta có thể lý luận 1 cách "formally" (chính thức))
  - Reason (lý luận) about situation mean constructing arguments <ins>about them (about situation)</ins>. So that argument
  are valid and can be defended rigorously, or executed by on a machine. (<ins>Lý luận về 1 trạng thái</ins> có nghĩa là 
  <ins>xây dựng các argument cho trạng thái ấy</ins>. Các argument thì đúng, có thể được bảo vệ chặt chẽ, hoặc dc chạy trên 1 cái máy). 
  - Trong phát triển logic, chúng ta không lo lắng về ý nghĩa thực sự của câu, chúng ta chỉ quan tâm cấu trúc logic của câu.

## 1.1 Declarative sentences (câu khai báo)
- Câu khai báo, là câu có thể xem xét nó là đúng hay sai.


- Declarative sentences example:

  - (1) The sum of the numbers 3 and 5 equals 8.
  - (2) Jane reacted violently to Jack’s accusations.
  - (3) Every even natural number >2 is the sum of two prime numbers.
  - (4) All Martians like pepperoni on their pizza

- None-declarative sentences example:
  - Could you please pass me the salt?
  - Ready, steady, go!
  - May fortune come your way

- Từ các câu khai báo nguyên (atomic sentence), chúng ta có thể kết hợp để tạo ra câu phức tạp hơn.
Ví dụ:
  - p: ‘I won the lottery last week.’
  - q: ‘I purchased a lottery ticket.’
  - r: ‘I won last week’s sweepstakes.’

  Chúng ta có thể tạo thành các câu phức tạp hơn theo quy tắc dưới đây:
  - ¬: The negation of p is denoted by ¬p and expresses ‘I did not win the lottery
    last week,’ or equivalently ‘It is not true that I won the lottery last week.’
  - ∨: Given p and r we may wish to state that at least one of them is true: ‘I won the
    lottery last week, or I won last week’s sweepstakes;’ we denote this declarative
    sentence by p ∨ r and call it the disjunction of p and r2.
  - ∧: Dually, the formula p ∧ r denotes the rather fortunate conjunction of p and r:
    ‘Last week I won the lottery and the sweepstakes.’
  - →: Last, but definitely not least, the sentence ‘If I won the lottery last week,
    then I purchased a lottery ticket.’ expresses an implication between p and q,
    suggesting that q is a logical consequence of p. We write p → q for that3. We
    call p the assumption of p → q and q its conclusio
  Ví dụ:
    - (p ∧ q) → ((¬r) ∨ q)

## 1.2 Natural deduction (suy luận tự nhiên)


## 1.3 Propositional logic as a formal language (Mệnh đề logic như 1 ngôn ngữ chính thức)
## 1.4 Semantics of propositional logic (Ngữ nghĩa của logic mệnh đề)
## 1.5 Normal forms (Dạng bình thường)
## 1.6 SAT solvers
## 1.7 Exercises
## 1.8 Bibliographic notes
