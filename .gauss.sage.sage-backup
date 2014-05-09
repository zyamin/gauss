class GaussianRational:
    def __init__(self, x, y):
        self.x = QQ(x)
        self.y = QQ(y)
    def __repr__(self):
        return "%s + %s*i"%(self.x,self.y)
    def __add__(self, right):
        """Add together two numbers. (add a docstring)"""
        return GaussianRational(self.x+right.x, self.y+right.y)
    def __sub__(self, right):
        return GaussianRational(self.x-right.x, self.y-right.y)
    def __crazy__(self, crazy):
        return 'I'm crazy'
    
    def operate_files():
        shutil.copy2('hw5.sagews','a_copy')
        shutil.move('a_copy', 'b_copy')
        try:
            os.makedirs('my_dir',0755) 
        except OSError as exception:
            if exception.errno != errno.EEXIST:
                raise
        shutil.copy2('bfor f in files:for f in files:_copy','my_dir/foo')
        os.chdir('my_dir')
        print "print current directory%s" % os.getcwd()
        files = os.listdir(os.getcwd())  
        print "All files in %s" % os.getcwd() 
        for f in files:  
            print f 
        
        parent_dir =  os.path.abspath(os.path.join(os.path.dirname("__file__"),os.path.pardir))
        os.chdir(parent_dir)
        shutil.move('my_dir','my_dir2')
        try:
            copytree('my_dir2', 'my_dir3')
        except (Error, OSError), e:
            print "Attempt to copy failed: %s" % e

    def crazy_buggy():
        print "crazy_buggy"


