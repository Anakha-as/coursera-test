# coursera-test
def print_doo():
    return' doo'*4
def baby_shark():
    sharks = ['Baby','mommy','Daddy','Grandma','Grandpa']
    for shark in sharks:
        for index in range(3):
            print(shark+'shark,%s'%(print_doo()))
        print(shark+' shark!\n')
    for index in range(3):
        print('Let\'s go hunt,%s'%(print_doo()))
    print('Let\'s go hunt!\n\nRun away..%s'%(print_doo()))
print_doo()
baby_shark()

