all: restore publish-win publish-osx

restore:
	dotnet restore
publish-win:
	dotnet publish -r win10-x64 --output ../dist/win
publish-osx:
	dotnet publish -r osx.10.11-x64 --output ../dist/osx