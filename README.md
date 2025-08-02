# minshell_vis
### Debugging Stages:
1. **Tokenization** (`tokenize.c`) - Breaking input into tokens
2. **Syntax Validation** (`syntax_validation.c`) - Checking for errors
3. **Pipeline Parsing** (`parse_pipeline.c`) - Building command structure  
4. **AST Generation** (`execute_ast.c`) - Creating execution tree

## 🎯 Example Commands

Try these commands in the debugger:
- `ls -l`
- `cat file.txt | grep hello`
- `echo hello > output.txt`
- `cat << EOF`
- `ls | wc -l | cat`
- `grep pattern < input.txt > output.txt`

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- 42 School for the minishell project
- Built for educational purposes to help visualize shell parsing

---

**Made with ❤️ for  School students**