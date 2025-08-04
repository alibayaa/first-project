todo_list = []


def menu():
    print("Your To Do List")
    print("1. Add a task")
    print("2. View tasks")
    print("3. Complete a task")
    print("4. Delete a task")
    print("5. Exit")


print(menu())

choice = input("Enter your choice: ")


def add():
    task = input("Enter the task to add: ")
    todo_list.append(task)


def view():
    if todo_list == []:
        print("List is emppty.")
    else:
        print(todo_list)


def delete():
    x = input("What would you like to delete?: ")
    if x in todo_list:
        todo_list.remove(x)
    else:
        print("Task not found")


def complete():
    x = input("Which task is completed?: ")
    todo_list.remove(x)
    print("Congratulations!")


def exit():
    print("Bye Bye!")


if choice == "1":
    add()
elif choice == "2":
    view()
elif choice == "3":
    complete()
elif choice == "4":
    delete()
elif choice == "5":
    exit()
