## Question 1

Dùng python, đọc [video](https://www.youtube.com/watch?v=qbcYQSezLuY) và xuất ra các outputs sau:

- [ ] toạ độ bắt đầu của bi
- [ ] toạ độ kết thúc của bi
- [ ] toạ độ lúc bi chạm băng 1
- [ ] toạ độ lúc bi chạm băng 2
- [ ] toạ độ lúc bi chạm băng 3
- [ ] góc chạm băng khi bi chạm băng 1
- [ ] góc chạm băng khi bi chạm băng 2
- [ ] góc chạm băng khi bi chạm băng 3
- [ ] góc phản xạ khi bi chạm băng 1
- [ ] góc phản xạ khi bi chạm băng 2
- [ ] góc phản xạ khi bi chạm băng 3

![Illustration](https://github.com/bismuth1991/billards/blob/main/illustration.png?raw=true)


## Question 2

Dùng Python, đọc [video](https://www.youtube.com/watch?v=qbcYQSezLuY) và xuất ra toạ độ của bi theo thời gian, interval 100ms
```ts
  type Output = Array<{
    timeMs: number // 0, 100, 200, etc.
    coordinate: {
      x: number // float
      y: number // float
    }
  }>
```
