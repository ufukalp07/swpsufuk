'''bash 
ls ~/ | grep '^[A-Z]'''
'''bash
ls -a ~/ | grep '^\.'''
'''bash
ls -a ~/ | grep '^\.' | wc -l'''
'''bash
ls ~/ | grep '^[a-zA-Z]*$'''
'''bash
ls ~/ | grep '^[^A-Z]*$'''
'''bash
ls ~/ | grep -v '\.[a-zA-Z]\{3\}$'''
'''bash
ls /etc | grep '^c.*y$'''
'''bash
ls /etc | grep 'ss' '''
'''bash
ls ~/ | grep '^.\{1\}[A-Z].\{1\}[A-Z].e$'''
'''bash
ls ~/ | grep '^[a-zA-Z0-9]\{4\}$'''
'''bash
ls /var/log | grep '\.log$'''
