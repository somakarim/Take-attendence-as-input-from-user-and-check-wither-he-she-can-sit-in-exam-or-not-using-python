# Take-attendence-as-input-from-user-and-check-wither-he-she-can-sit-in-exam-or-not-using-python
NumClasses= input('Enter the Number of classes held: ')
AttendClasses= input('Enter The Number Of Classes Attend: ')
Per= (int(AttendClasses)/int(NumClasses))*100
if Per>=75:
  print('You can sit in Exam.')
else:
  print('You can not sit in Exam')
