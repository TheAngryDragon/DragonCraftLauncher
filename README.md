<p align="center">
  
</p>

DragonCraft
=======

DragonCraft is a custom launcher for Minecraft that focuses on predictability, long term stability and simplicity.

## Disclaimer

This is a Fork of MuktiMC. We have taken it upon ourselves to fix issues that the original devs are no longer able to.

The Developers of MultiMC are not in anyway related, or in any way, part of this fork, and as such should not be held accountable for any code changes made since this fork was created. We disavow any permission or implied blessing the Developers of the MultiMC project may or may not have given this fork.

### Building
If you want to build the launcher yourself, check [BUILD.md](BUILD.md) for build instructions.

### Code formatting
Just follow the existing formatting.

In general, in order of importance:
* Make sure your IDE is not messing up line endings or whitespace and avoid using linters.
* Prefer readability over dogma.
* Keep to the existing formatting.
* Indent with 4 space unless it's in a submodule.
* Keep lists (of arguments, parameters, initializers...) as lists, not paragraphs. It should either read from top to bottom, or left to right. Not both.

## License
Copyright &copy; 2022 DragonCraft Contributors

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this program except in compliance with the License. You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Forking/Redistributing/Custom builds policy
We keep Launcher open source because we think it's important to be able to see the source code for a project like this, and we do so using the Apache license.

The license gives you access to the source DragonCraft is build from, but:
- Not the name, logo and other branding.
- Not the API tokens required to talk to services the launcher depends on.

Because of the nature of the agreements required to interact with the Microsoft identity platform, it's impossible for us to continue allowing everyone to build the code as 'DragonCraft'. The source code has been debranded and now builds as `DevLauncher` by default.

You must provide your own branding if you want to distribute your own builds.

You will also have to register your own app on Azure to be able to handle Microsoft account logins.

If you decide to fork the project, a mention of its origins in the About dialog and the license is acceptable. However, it should be abundantly clear that the project is a fork *without* implying that you have our blessing.
