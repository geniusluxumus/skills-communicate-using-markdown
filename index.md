# Header 1
## Header 2

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


```python
# Passing a List to a Function

messages = ['Baltok ka', 'Gwapo ka', 'Pogi ka', 'Riko ka']
sent_messages = []


# Passing a List to a Function
messages = ['Baltok ka', 'Gwapo ka', 'Pogi ka', 'Riko ka']
sent_messages = []


def show_message(message):
    for message in messages:
        print(message)


def send_message(message):
    while message:
        current_message = message.pop()
        print(f"Sent Message: {current_message}")
        sent_messages.append(current_message)


show_message(messages)
send_message(messages)  # put [:] to make it retain the messages list elements
print(messages)  # this will be null if no [:] is used
print(sent_messages)

```
