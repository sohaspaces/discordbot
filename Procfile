installer:   curl -sSL https://dotnetcli.blob.core.windows.net/dotnet/Sdk/5.0.101/dotnet-sdk-5.0.101-linux-x64.tar.gz | tar xz -C $HOME/dotnet/5.0.101/sdk && find  $HOME/dotnet/5.0.101/sdk/sdk/5.0.101/runtimes/* -maxdepth 0 ! -name unix -exec rm -r {} + && rm -f $HOME/dotnet/5.0.101/sdk/sdk/$5.0.101/nuGetPackagesArchive.lzma &&curl -sSL https://dotnetcli.blob.core.windows.net/dotnet/Runtime/5.0.1/dotnet-runtime-5.0.1-linux-x64.tar.gz  | tar xz -C $HOME/dotnet/5.0.101/runtime && export PATH="$HOME/dotnet/5.0.101/sdk:$PATH" && mkdir -p $HOME/.heroku/dotnet && cp -r $HOME/dotnet/5.0.101/runtime $HOME/.heroku/dotnet
