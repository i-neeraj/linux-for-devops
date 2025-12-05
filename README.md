# linux-for-devops
This is how i practice linux for devops.


ls              # list files
ls -l           # detailed list
cd <folder>     # go inside folder
cd ..           # go back one step
pwd             # show current path
mkdir myfolder  # create folder
rm file.txt     # delete file
rm -r folder    # delete folder

cat file.txt        # show file content
nano file.txt       # edit file
head file.txt       # first 10 lines
tail file.txt       # last 10 lines
tail -f log.txt     # live logs
cp a.txt b.txt      # copy file
mv a.txt b.txt      # rename/move file

sudo su             # switch to root
chmod 755 file      # change permissions
chown user:user file  # change owner


sudo apt update
sudo apt upgrade -y

sudo apt install nginx -y

sudo systemctl start nginx

sudo systemctl enable nginx

systemctl status nginx
