---
layout: post
title: Gradient desent là gì?
date: 2018-08-12
categories: jekyll update
---

# Gradient descents là gì?
Gradient descents là một thuật toán tối ưu thường được sử dụng để tìm weight hoặc các hệ số tối ưu trong các thuật toán machine learning.

Mục tiêu của gradient desents là tìm gía trị nhỏ nhất của hàm mất mát theo các tham số weight và bias.

**Thuật toán gradient desents:**

Mục tiêu tìm local minimum của hàm \(f(\mathbf{\theta})\)
1. Khởi tạo gía trị \(\theta = \theta_{0}\)
2. Cập nhật \(\theta\) đến khi có kết quả chấp nhận được: \(\theta_new = \theta_old - \eta \theta \nabla_{\theta}f(\theta)\)