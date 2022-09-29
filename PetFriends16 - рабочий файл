from Pets import Cat, Dog, Bird
Cat1=Cat('Sam','Sibir kat',2,'free')
Dog1=Dog('Felix','Pitbul',2,'busy')
Dog2=Dog('Muhtar','German Ovcharka',0,'busy')
Cat2=Cat('Bob','Sibir kat',2,'free')
Bird1=Bird('Gosha','Korella',0,'free')
Cat3=Cat('Sasha','Sibir kat',2,'busy')

PETS=(Cat1,Dog1,Dog2,Cat2,Bird1,Cat3)

print("\nсписок свободных питомцев:\n_______________")
for pet in PETS:
    if pet.condition=='free':
        print('Имя:',pet.name,'\nПорода:',pet.breed,'\nВозраст:',pet.age,'\nСтатус:',pet.condition,'\n_______________')
print('\n')
print("\nсписок занятых питомцев:\n_______________")
for pet in PETS:
    if pet.condition=='busy':
        print('Имя:',pet.name,'\nПорода:',pet.breed,'\nВозраст:',pet.age,'\nСтатус:',pet.condition,'\n_______________')
#Функция проверки isinstance,Она проверяет, является ли аргумент объекта экземпляром класса)
for pet in PETS:
    if isinstance(pet,Cat):
        print('Имя:', pet.name, '\nПорода:', pet.breed, '\nВозраст:', pet.age, '\nСтатус:', pet.condition,'\n_______________')
    if isinstance(pet,Dog):
        print('Имя:', pet.name, '\nПорода:', pet.breed, '\nВозраст:', pet.age, '\nСтатус:', pet.condition,'\n_______________')
    else:
        print('Имя:', pet.name, '\nПорода:', pet.breed, '\nВозраст:', pet.age, '\nСтатус:', pet.condition,'\n_______________')
