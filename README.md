ubuntu@ubuntu-VMware-Virtual-Platform:~$ source myenv/bin/activate
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ git status
현재 브랜치 master
추적하지 않는 파일:
  (커밋할 사항에 포함하려면 "git add <파일>..."을 사용하십시오)
	.bash_history
	.bash_logout
	.bashrc
	.cache/
	.config/
	.dotnet/
	.gitconfig
	.local/
	.pki/
	.profile
	.python_history
	.ssh/
	.sudo_as_admin_successful
	.vscode/
	Cal/
	myenv/
	open/__pycache__/
	snap/
	"\353\213\244\354\232\264\353\241\234\353\223\234/"
	"\353\254\270\354\204\234/"

커밋할 사항을 추가하지 않았지만 추적하지 않는 파일이 있습니다 (추적하려면 "git
add"를 사용하십시오)
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ git checkout master
이미 'master'에 있습니다
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ ^[[200~git merge main --allow-unrelated-histories
git: 명령을 찾을 수 없습니다
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ git merge main --allow-unrelated-histories
merge: main - 병합할 수 있는 항목이 아닙니다
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ git checkout master
이미 'master'에 있습니다
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ rm -rf .git
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ git init
힌트: Using 'master' as the name for the initial branch. This default branch name
힌트: is subject to change. To configure the initial branch name to use in all
힌트: of your new repositories, which will suppress this warning, call:
힌트: 
힌트: 	git config --global init.defaultBranch <name>
힌트: 
힌트: Names commonly chosen instead of 'master' are 'main', 'trunk' and
힌트: 'development'. The just-created branch can be renamed via this command:
힌트: 
힌트: 	git branch -m <name>
/home/ubuntu/.git/ 안의 빈 깃 저장소를 다시 초기화했습니다
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~$ cd open
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ rm -rf .git
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ git init
힌트: Using 'master' as the name for the initial branch. This default branch name
힌트: is subject to change. To configure the initial branch name to use in all
힌트: of your new repositories, which will suppress this warning, call:
힌트: 
힌트: 	git config --global init.defaultBranch <name>
힌트: 
힌트: Names commonly chosen instead of 'master' are 'main', 'trunk' and
힌트: 'development'. The just-created branch can be renamed via this command:
힌트: 
힌트: 	git branch -m <name>
/home/ubuntu/open/.git/ 안의 빈 깃 저장소를 다시 초기화했습니다
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ git add *
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ git commit -m "ubuntu"
[master (최상위-커밋) 5e95cd5] ubuntu
 8 files changed, 66 insertions(+)
 create mode 100644 __pycache__/Control.cpython-312.pyc
 create mode 100644 __pycache__/Ctrl.cpython-312.pyc
 create mode 100644 __pycache__/ctrl.cpython-312.pyc
 create mode 100644 __pycache__/ui.cpython-312.pyc
 create mode 100644 ctrl.py
 create mode 100644 icon.png
 create mode 100644 main.py
 create mode 100644 ui.py
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ git remote add origin https://github.com/kohmatoro/ubuntu
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ git branch -m main
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ git push -f origin main
Username for 'https://github.com': kohmatoro
Password for 'https://kohmatoro@github.com': 
오브젝트 나열하는 중: 11, 완료.
오브젝트 개수 세는 중: 100% (11/11), 완료.
Delta compression using up to 2 threads
오브젝트 압축하는 중: 100% (11/11), 완료.
오브젝트 쓰는 중: 100% (11/11), 6.72 KiB | 6.72 MiB/s, 완료.
Total 11 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/kohmatoro/ubuntu
 + 92577b8...5e95cd5 main -> main (forced update)
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ code
(myenv) ubuntu@ubuntu-VMware-Virtual-Platform:~/open$ 
