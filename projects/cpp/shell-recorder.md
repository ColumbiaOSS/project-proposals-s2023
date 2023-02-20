# shell-recorder

## Basic features

- when execute the tool for the first time, the shell recording is on and all Commands and output generated afterwards are recorded
- when execute the tool for the second time, the shell recording is off and a file containing all logs in the recording period is saved
  - user should be able to choose the output file content coverage (for example, shell's in/out/error...)
  - user should be able to set the output file type and path
  - user should be able to select a layout for the output file (for example, markdown as lecture note, shell scripts for future use)

## Advanced features

- Automatic text typesetting
- Automatic generation of executable configuration files, shell scripts, etc.
- A local or online database or storage system to manage these recordings

## Application Scenarios

- classroom demonstration recording
  - In computer teaching, the teacher's time to demonstrate new methods and codes is always shorter than the students' time to understand the content. So recording the teacher's input and output in the shell over a period of time makes it easy to understand the text version of the instruction.
  - Teachers don't have to drag and drop the shell and struggle to copy the entire presentation. More over, auto-typesetting is enabled to hand over the file as course material more easily.

- instruction set recording
  - When configuring a new environment and familiarizing yourself with a new tool, you will always watch a tutorial and enter a series of unfamiliar commands. Usually we do not check the feasibility of each command until after we succeed and neglect to save the common set of feasible commands, which leads to duplication of efforts when we encounter the same work later.
  - The tool can record successfully typed commands over a period of time and generate shell scripts for saving and reuse.
  - Even if a command is entered incorrectly, the output error log can be saved to guide future work more easily.

  [ShellRecorder](https://github.com/Erisae/ShellRecorder)
