# branch�̍쐬�E�폜�̕��@

1. git Bash ���N�����܂��傤
   
   ![hoge](/Image/execute_git_bash.png) <br><br>

2. branch����郊�|�W�g���[�ֈړ����܂��傤
user�̃f�B���N�g���[����ł���Έȉ��̃R�}���h�ňړ��ł��܂��B<br>
�������ONE_DOCUMENT��branch������Ă݂��B<br>

   ```sh
   cd git/ONE_DOCUMENT
   ```
   �ȉ��̂悤��`ONE_DOCUMENT`�̃f�B���N�g���[�ɂ����OK<br>
   �����M�҂̊��ł�`work/`�z���ɂ���̂ŉ��L�̂悤�ɂȂ��Ă���B<br>
   ������`ONE_DOCUMENT`�̌���`main`�ɂ����ځB<br>
   �����ɂ͌��݂��鎩���̂���`branch`���\�������B
   ![hoge](/image/cd_repository.png)

3. `main branch`���x�[�X�ɐV����`branch`����낤�B<br>
   �ȉ��R�}���h��**�����鎩���̂���branch**���x�[�X��branch����邱�Ƃ��ł���B <br>
   `[branch_name]`�̉ӏ��͔C�ӂ̖��O�ɒu�������悤�B
   ### �u�����`�����K�� <br>
   ��{�I�Ɉȉ��̒ʂ薽�������邱��<br>
   `yyyymmdd_UserName_BranchName`<br>
   BranchName�͕ύX�_���킩��₷�����O�ɂ��邱��<br>


   ```sh
   git checkout -b [branch_name]
   ```
   �ȉ��̂悤��`branch`���쐬�ł���ƍ쐬����`branch`�ɐ؂�ւ��<br>

   ![hoge](/image/checkout_mk_branch.png)

   
4. `branch`�̈ꗗ���m�F����B<br>
   `git branch`�R�}���h�Ŋm�F�ł���B
   ```sh
   git branch
   ```
   ![hoge](Image/../../Image/show_branch.png)

5. `main branch`�ֈړ�
   `git checkout`�R�}���h�ňړ����悤�B<br>
   �f�B���N�g���[���̉E����`(main)`�ɂȂ��OK
   ```sh
   git checkout [branch_name]
   ```
   ![hoge](/Image/switch_branch.png)

6. �쐬����branch���폜<br>
   �Ƃ��� `branch -D`�R�}���h�ōs����<br>
   `-D`�̕����͑啶���A�������ňӖ����ς��̂Œ��ӂ��܂��傤�B
   ```
   git branch -D [branch_name]
   ```
   �폜�������`git branch`�����s���č폜���ꂽ���Ƃ��m�F
   ![hoge](/image/delete_branch.png)

�@�@
7. �`���[�g���A���I��
   