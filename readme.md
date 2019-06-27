new python terminal commands learnt

to remove/reset migrations from the terminal;

1. python manage.py shell
2. from core.models import Journal
3. Journal.objects.all().delete()
4. exit
5. make migrations etc
6. python manage.py create_data title