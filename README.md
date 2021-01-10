# Attendence-Percentage-Calulator
This is a attendence percentage calulatorit will calculate percentage with your input

a=int(input('Total number of students: '))
b=int(input('Number of students present: '))
percent = (b/a) * 100
def repeath():
                a=int(input('Total number of students: '))
                b=int(input('Number of students present: '))
                percent = (b/a) * 100
                if percent > 100 or percent < 0:
                                print('wrong value')
                                repeath()
                elif percent == 100:
                                print('100% attendance!')
                elif percent == 0:
                                print('no worry they will come tommorrow')
                else:
                                print("The percentage of students present today are" , percent , '%')
                                
if percent > 100 or percent < 0:
                print('wrong value')
                repeath()
elif percent == 100:
                print('100% attendance!')
elif percent == 0:
                print('No worry they will come tommorrow')
else:
                print("percentage of students present today are" , percent , '%')
