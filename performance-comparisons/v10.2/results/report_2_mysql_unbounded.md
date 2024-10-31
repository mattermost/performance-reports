### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 8ms | 150ms | 142ms | 1711.95
| RetentionPolicyStore.GetAll | avg | 17ms | 266ms | 249ms | 1444.38
| PluginStore.Get | avg | 99ms | 591ms | 492ms | 498.12
| ChannelStore.GetMembersForUserWithPagination | avg | 167ms | 977ms | 810ms | 486.03
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 38ms | 202ms | 164ms | 434.59
| TokenStore.Cleanup | avg | 7ms | 30ms | 23ms | 343.20
| CommandWebhookStore.Cleanup | avg | 7ms | 27ms | 20ms | 296.54
| ChannelStore.CreateSidebarCategory | avg | 72ms | 241ms | 169ms | 235.02
| UserStore.GetProfilesInChannel | avg | 49ms | 153ms | 104ms | 214.42
| PostStore.SetPostReminder | avg | 9ms | 23ms | 14ms | 157.49
| EmojiStore.GetMultipleByName | avg | 98ms | 246ms | 148ms | 150.73
| UserAccessTokenStore.GetByToken | avg | 17ms | 36ms | 19ms | 109.53
| PostPersistentNotificationStore.DeleteExpired | avg | 3ms | 6ms | 3ms | 102.38
| ProductNoticesStore.GetViews | avg | 136ms | 208ms | 72ms | 52.88
| SessionStore.Remove | avg | 5ms | 7ms | 2ms | 40.41
| SessionStore.GetSessionsExpired | avg | 99ms | 137ms | 38ms | 38.40
| PostStore.Delete | avg | 159ms | 192ms | 33ms | 20.75
| JobStore.GetCountByStatusAndType | avg | 103ms | 123ms | 20ms | 19.50
| ChannelStore.GetMembers | avg | 72ms | 85ms | 13ms | 18.05
| ChannelStore.UpdateSidebarCategories | avg | 255ms | 290ms | 35ms | 13.70
| ChannelStore.AnalyticsTypeCount | avg | 69ms | 78ms | 9ms | 13.10
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 145ms | 163ms | 18ms | 12.40
| RoleStore.GetByNames | avg | 142ms | 152ms | 10ms | 7.06
| ChannelStore.GetSidebarCategory | avg | 138ms | 146ms | 8ms | 5.79
| PreferenceStore.GetAll | avg | 146ms | 152ms | 6ms | 4.12
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 10ms | 247ms | 237ms | 2381.91
| RetentionPolicyStore.GetAll | p99 | 25ms | 498ms | 473ms | 1903.42
| PluginStore.Get | p99 | 247ms | 4.85s | 4.603s | 1863.56
| ChannelStore.GetMembersForUserWithPagination | p99 | 487ms | 4.875s | 4.388s | 900.10
| UserStore.GetProfilesInChannel | p99 | 238ms | 2.35s | 2.112s | 887.31
| EmojiStore.GetMultipleByName | p99 | 247ms | 2.17s | 1.923s | 777.95
| PostStore.SetPostReminder | p99 | 47ms | 236ms | 189ms | 401.06
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 228ms | 943ms | 715ms | 313.96
| CommandWebhookStore.Cleanup | p99 | 24ms | 98ms | 74ms | 303.28
| TokenStore.Cleanup | p99 | 24ms | 98ms | 74ms | 303.28
| UserAccessTokenStore.GetByToken | p99 | 244ms | 595ms | 351ms | 143.85
| JobStore.GetCountByStatusAndType | p99 | 610ms | 1.36s | 750ms | 122.95
| JobStore.UpdateStatusOptimistically | p99 | 67ms | 137ms | 70ms | 104.49
| ChannelStore.CreateSidebarCategory | p99 | 247ms | 495ms | 248ms | 100.40
| SessionStore.GetSessionsExpired | p99 | 478ms | 945ms | 467ms | 97.80
| PostStore.Delete | p99 | 489ms | 967ms | 478ms | 97.68
| RoleStore.ChannelHigherScopedPermissions | p99 | 902ms | 1.754s | 852ms | 94.49
| SessionStore.Remove | p99 | 46ms | 86ms | 40ms | 86.96
| ComplianceStore.MessageExport | p99 | 939ms | 1.734s | 795ms | 84.69
| JobStore.GetNewestJobByStatusesAndType | p99 | 770ms | 1.353s | 583ms | 75.71
| ChannelStore.SearchGroupChannels | p99 | 997ms | 1.524s | 527ms | 52.86
| ChannelStore.Save | p99 | 996ms | 1.458s | 462ms | 46.38
| ChannelStore.GetMember | p99 | 108ms | 157ms | 49ms | 45.21
| RoleStore.GetByNames | p99 | 852ms | 1.053s | 201ms | 23.60
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 1.473s | 1.78s | 307ms | 20.85
| FileInfoStore.SetContent | p99 | 98ms | 117ms | 19ms | 19.39
| PostPriorityStore.GetForPost | p99 | 910ms | 1.085s | 175ms | 19.23
| UserStore.GetUnreadCount | p99 | 980ms | 1.142s | 162ms | 16.54
| GroupStore.GetGroups | p99 | 1.163s | 1.318s | 155ms | 13.32
| JobStore.Get | p99 | 1.594s | 1.785s | 191ms | 11.99
| PostStore.GetPostsByThread | p99 | 1.308s | 1.464s | 156ms | 11.93
| PostPersistentNotificationStore.DeleteExpired | p99 | 80ms | 89ms | 9ms | 11.25
| ThreadStore.GetThreadUnreadReplyCount | p99 | 1.282s | 1.417s | 135ms | 10.53
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 889ms | 979ms | 90ms | 10.12
| ChannelStore.Get | p99 | 1.487s | 1.637s | 150ms | 10.09
| UserStore.GetAllProfiles | p99 | 781ms | 846ms | 65ms | 8.32
| PostAcknowledgementStore.GetForPost | p99 | 876ms | 941ms | 65ms | 7.42
| ReactionStore.GetForPost | p99 | 973ms | 1.037s | 64ms | 6.58
| ThreadStore.GetThreadsForUser | p99 | 1.381s | 1.467s | 86ms | 6.23
| PostStore.GetPostIdAfterTime | p99 | 51ms | 54ms | 3ms | 5.87
| ChannelStore.UpdateSidebarCategories | p99 | 2.08s | 2.163s | 83ms | 3.99
| DraftStore.Upsert | p99 | 76ms | 79ms | 3ms | 3.95
| PreferenceStore.GetAll | p99 | 1.112s | 1.145s | 33ms | 2.97
| DraftStore.Delete | p99 | 71ms | 73ms | 2ms | 2.81
| FileInfoStore.Save | p99 | 75ms | 77ms | 2ms | 2.68
| EmojiStore.GetByName | p99 | 1.121s | 1.151s | 30ms | 2.68
| PostStore.Get | p99 | 2.118s | 2.174s | 56ms | 2.64
| ChannelStore.CreateInitialSidebarCategories | p99 | 878ms | 900ms | 22ms | 2.50
| TeamStore.GetTeamsByUserId | p99 | 875ms | 894ms | 19ms | 2.17
| DraftStore.Get | p99 | 1.616s | 1.65s | 34ms | 2.10
| TeamStore.GetTotalMemberCount | p99 | 960ms | 977ms | 17ms | 1.77
| ChannelStore.GetMemberForPost | p99 | 1.54s | 1.567s | 27ms | 1.75
| ChannelStore.GetMembers | p99 | 242ms | 246ms | 4ms | 1.65
| UserStore.GetProfileByIds | p99 | 866ms | 877ms | 11ms | 1.27
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | avg | 299ms | 0s | -299ms | -100.03
| ChannelStore.GetMemberCountsByGroup | avg | 7ms | 0s | -7ms | -99.29
| ThreadStore.MarkAllAsReadByTeam | avg | 9ms | 2ms | -7ms | -78.36
| PostStore.GetPostReminders | avg | 17ms | 4ms | -13ms | -74.95
| ChannelStore.GetByNameIncludeDeleted | avg | 131ms | 40ms | -91ms | -69.41
| PreferenceStore.DeleteCategoryAndName | avg | 9ms | 3ms | -6ms | -67.11
| PostStore.GetPostReminderMetadata | avg | 182ms | 80ms | -102ms | -56.19
| UserStore.Update | avg | 13ms | 6ms | -7ms | -54.77
| ChannelStore.GetChannelUnread | avg | 134ms | 75ms | -59ms | -44.01
| LinkMetadataStore.Save | avg | 8ms | 5ms | -3ms | -39.28
| PluginStore.List | avg | 158ms | 98ms | -60ms | -37.93
| ThreadStore.MarkAllAsReadByChannels | avg | 6ms | 4ms | -2ms | -35.95
| ChannelStore.GetTeamChannels | avg | 282ms | 184ms | -98ms | -34.76
| UserStore.Count | avg | 447ms | 292ms | -155ms | -34.69
| ChannelStore.GetAllChannelMembersForUser | avg | 106ms | 70ms | -36ms | -33.89
| UserStore.GetProfilesNotInChannel | avg | 57ms | 38ms | -19ms | -33.43
| PostStore.AnalyticsPostCount | avg | 2.699s | 1.803s | -896ms | -33.20
| JobStore.Save | avg | 6ms | 4ms | -2ms | -32.63
| ChannelStore.Autocomplete | avg | 4.691s | 3.164s | -1.527s | -32.55
| UserStore.AnalyticsActiveCount | avg | 671ms | 462ms | -209ms | -31.15
| ChannelStore.CreateDirectChannel | avg | 483ms | 338ms | -145ms | -30.04
| ComplianceStore.MessageExport | avg | 115ms | 81ms | -34ms | -29.45
| FileInfoStore.GetByIds | avg | 195ms | 138ms | -57ms | -29.28
| UserStore.GetMany | avg | 200ms | 142ms | -58ms | -29.05
| TeamStore.GetActiveMemberCount | avg | 546ms | 390ms | -156ms | -28.59
| ClusterDiscoveryStore.SetLastPingAt | avg | 7ms | 5ms | -2ms | -28.35
| TeamStore.GetMember | avg | 7ms | 5ms | -2ms | -27.72
| ChannelStore.GetPinnedPostCount | avg | 159ms | 115ms | -44ms | -27.65
| ChannelStore.GetChannelsByUser | avg | 138ms | 101ms | -37ms | -26.91
| UserStore.Get | avg | 65ms | 48ms | -17ms | -26.17
| StatusStore.UpdateExpiredDNDStatuses | avg | 8ms | 6ms | -2ms | -25.84
| PostStore.SearchPostsForUser | avg | 288ms | 215ms | -73ms | -25.33
| ThreadStore.Get | avg | 178ms | 135ms | -43ms | -24.19
| JobStore.Get | avg | 169ms | 129ms | -40ms | -23.65
| PostStore.GetPostsAfter | avg | 117ms | 90ms | -27ms | -23.07
| PostAcknowledgementStore.GetForPost | avg | 136ms | 105ms | -31ms | -22.77
| FileInfoStore.Get | avg | 105ms | 83ms | -22ms | -20.92
| UserStore.AnalyticsGetInactiveUsersCount | avg | 76ms | 61ms | -15ms | -19.87
| ChannelStore.GetFileCount | avg | 111ms | 89ms | -22ms | -19.80
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 790ms | 637ms | -153ms | -19.36
| JobStore.GetAllByTypePage | avg | 176ms | 142ms | -34ms | -19.35
| ChannelStore.AutocompleteInTeamForSearch | avg | 617ms | 498ms | -119ms | -19.29
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 26ms | 21ms | -5ms | -19.24
| TeamStore.GetTeamsForUser | avg | 85ms | 69ms | -16ms | -18.85
| UserStore.Search | avg | 413ms | 337ms | -76ms | -18.42
| BotStore.Get | avg | 136ms | 111ms | -25ms | -18.34
| ThreadStore.GetThreadForUser | avg | 225ms | 185ms | -40ms | -17.75
| UserStore.GetProfilesByUsernames | avg | 114ms | 94ms | -20ms | -17.53
| DraftStore.GetDraftsForUser | avg | 172ms | 142ms | -30ms | -17.47
| UserStore.AutocompleteUsersInChannel | avg | 793ms | 656ms | -137ms | -17.27
| UserStore.GetAllProfilesInChannel | avg | 1.325s | 1.099s | -226ms | -17.05
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 183ms | 152ms | -31ms | -16.98
| ChannelStore.GetMemberCount | avg | 573ms | 477ms | -96ms | -16.75
| PostStore.GetPostsSince | avg | 196ms | 164ms | -32ms | -16.30
| PostStore.GetSingle | avg | 144ms | 121ms | -23ms | -15.97
| PostStore.GetPostsBefore | avg | 145ms | 122ms | -23ms | -15.87
| SessionStore.Save | avg | 102ms | 86ms | -16ms | -15.76
| StatusStore.GetByIds | avg | 181ms | 153ms | -28ms | -15.51
| ThreadStore.GetMembershipForUser | avg | 149ms | 126ms | -23ms | -15.47
| PostAcknowledgementStore.GetForPosts | avg | 231ms | 196ms | -35ms | -15.12
| ThreadStore.GetThreadUnreadReplyCount | avg | 153ms | 130ms | -23ms | -15.05
| LinkMetadataStore.Get | avg | 146ms | 124ms | -22ms | -15.02
| PostStore.GetPostsByThread | avg | 149ms | 127ms | -22ms | -14.81
| PostPriorityStore.GetForPosts | avg | 237ms | 202ms | -35ms | -14.79
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 130ms | 111ms | -19ms | -14.65
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 116ms | 99ms | -17ms | -14.60
| PostPriorityStore.GetForPost | avg | 124ms | 106ms | -18ms | -14.48
| TeamStore.Get | avg | 139ms | 119ms | -20ms | -14.35
| PreferenceStore.Get | avg | 138ms | 119ms | -19ms | -13.75
| FileInfoStore.GetForPost | avg | 169ms | 146ms | -23ms | -13.59
| ChannelStore.GetMembersForUser | avg | 142ms | 123ms | -19ms | -13.36
| PostStore.Get | avg | 243ms | 211ms | -32ms | -13.19
| SessionStore.GetLRUSessions | avg | 99ms | 86ms | -13ms | -13.13
| ChannelStore.Save | avg | 193ms | 168ms | -25ms | -12.94
| UserStore.GetUnreadCount | avg | 123ms | 108ms | -15ms | -12.24
| PostPersistentNotificationStore.GetSingle | avg | 156ms | 137ms | -19ms | -12.20
| ChannelStore.GetChannels | avg | 142ms | 125ms | -17ms | -11.97
| ThreadStore.GetThreadFollowers | avg | 151ms | 133ms | -18ms | -11.95
| WebhookStore.GetOutgoingByTeam | avg | 154ms | 136ms | -18ms | -11.68
| ThreadStore.GetThreadsForUser | avg | 165ms | 146ms | -19ms | -11.52
| TeamStore.AnalyticsTeamCount | avg | 70ms | 62ms | -8ms | -11.46
| DraftStore.Get | avg | 171ms | 153ms | -18ms | -10.51
| ThreadStore.GetTotalThreads | avg | 114ms | 102ms | -12ms | -10.49
| UserStore.IsEmpty | avg | 58ms | 52ms | -6ms | -10.29
| ChannelStore.GetMemberForPost | avg | 167ms | 150ms | -17ms | -10.18
| ThreadStore.GetTeamsUnreadForUser | avg | 143ms | 129ms | -14ms | -9.77
| EmojiStore.GetByName | avg | 147ms | 133ms | -14ms | -9.55
| PostStore.Update | avg | 21ms | 19ms | -2ms | -9.37
| GroupStore.GetGroups | avg | 142ms | 129ms | -13ms | -9.16
| ChannelStore.GetMemberLastViewedAt | avg | 98ms | 89ms | -9ms | -9.16
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 112ms | 102ms | -10ms | -8.94
| ThreadStore.GetTotalUnreadMentions | avg | 112ms | 102ms | -10ms | -8.93
| ChannelStore.SearchGroupChannels | avg | 163ms | 149ms | -14ms | -8.60
| TeamStore.GetTotalMemberCount | avg | 399ms | 365ms | -34ms | -8.51
| PostStore.GetEtag | avg | 142ms | 130ms | -12ms | -8.45
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 267ms | 245ms | -22ms | -8.22
| UserStore.GetForLogin | avg | 93ms | 86ms | -7ms | -7.51
| GroupStore.GetByName | avg | 81ms | 75ms | -6ms | -7.43
| ThreadStore.GetTotalUnreadThreads | avg | 110ms | 102ms | -8ms | -7.29
| StatusStore.Get | avg | 84ms | 78ms | -6ms | -7.13
| LicenseStore.GetAll | avg | 301ms | 280ms | -21ms | -6.99
| SessionStore.Get | avg | 108ms | 101ms | -7ms | -6.49
| ReactionStore.GetForPost | avg | 139ms | 130ms | -9ms | -6.48
| UserStore.GetProfileByIds | avg | 79ms | 74ms | -5ms | -6.33
| PostStore.GetPosts | avg | 97ms | 91ms | -6ms | -6.17
| ProductNoticesStore.View | avg | 34ms | 32ms | -2ms | -5.91
| ChannelStore.GetGuestCount | avg | 141ms | 133ms | -8ms | -5.68
| TeamStore.GetChannelUnreadsForAllTeams | avg | 106ms | 100ms | -6ms | -5.67
| ChannelStore.GetPublicChannelsForTeam | avg | 195ms | 184ms | -11ms | -5.64
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 105ms | 100ms | -5ms | -4.78
| ChannelStore.SaveMember | avg | 436ms | 418ms | -18ms | -4.13
| JobStore.GetAllByStatus | avg | 132ms | 127ms | -5ms | -3.78
| ChannelStore.GetByName | avg | 99ms | 97ms | -2ms | -2.02
| TeamStore.GetAllPage | avg | 107ms | 105ms | -2ms | -1.87
| UserTermsOfServiceStore.GetByUser | avg | 122ms | 120ms | -2ms | -1.64
| JobStore.GetNewestJobByStatusesAndType | avg | 122ms | 120ms | -2ms | -1.64
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | p99 | 88ms | 0s | -88ms | -100.00
| FileInfoStore.Search | p99 | 497ms | 0s | -497ms | -99.90
| PostStore.GetPostReminders | p99 | 213ms | 23ms | -190ms | -89.41
| ThreadStore.MarkAllAsReadByTeam | p99 | 25ms | 5ms | -20ms | -80.97
| ChannelStore.GetByNameIncludeDeleted | p99 | 249ms | 50ms | -199ms | -80.03
| UserStore.Update | p99 | 200ms | 49ms | -151ms | -75.31
| PostStore.GetPostReminderMetadata | p99 | 1.84s | 472ms | -1.368s | -74.35
| PreferenceStore.DeleteCategoryAndName | p99 | 91ms | 23ms | -68ms | -74.32
| ThreadStore.Get | p99 | 2.75s | 948ms | -1.802s | -65.53
| LinkMetadataStore.Save | p99 | 149ms | 53ms | -96ms | -64.22
| TeamStore.AnalyticsTeamCount | p99 | 247ms | 99ms | -148ms | -59.92
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 247ms | 99ms | -148ms | -59.92
| ChannelStore.AnalyticsTypeCount | p99 | 247ms | 100ms | -147ms | -59.51
| UserStore.GetProfilesNotInChannel | p99 | 244ms | 99ms | -145ms | -59.43
| PluginStore.List | p99 | 1.75s | 730ms | -1.02s | -58.29
| UserStore.GetMany | p99 | 2.155s | 905ms | -1.25s | -58.00
| UserStore.GetAllProfilesInChannel | p99 | 7.496s | 3.602s | -3.894s | -51.94
| PostStore.AnalyticsPostCount | p99 | 9.9s | 4.925s | -4.975s | -50.25
| BotStore.Get | p99 | 937ms | 468ms | -469ms | -50.03
| ChannelStore.GetSidebarCategory | p99 | 1.69s | 857ms | -833ms | -49.29
| ChannelStore.GetTeamChannels | p99 | 955ms | 489ms | -466ms | -48.80
| ChannelStore.GetPublicChannelsForTeam | p99 | 1.915s | 989ms | -926ms | -48.35
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 91ms | 49ms | -42ms | -45.90
| UserStore.AutocompleteUsersInChannel | p99 | 4.153s | 2.459s | -1.694s | -40.79
| DraftStore.GetDraftsForUser | p99 | 1.736s | 1.045s | -691ms | -39.81
| ChannelStore.AutocompleteInTeamForSearch | p99 | 4.019s | 2.476s | -1.543s | -38.40
| ChannelStore.GetChannelUnread | p99 | 1.359s | 856ms | -503ms | -37.01
| TeamStore.GetMember | p99 | 199ms | 130ms | -69ms | -34.63
| ChannelStore.GetMemberCount | p99 | 3.37s | 2.275s | -1.095s | -32.49
| PostStore.GetPostsAfter | p99 | 1.405s | 954ms | -451ms | -32.10
| ClusterDiscoveryStore.SetLastPingAt | p99 | 82ms | 57ms | -25ms | -30.54
| ChannelStore.GetChannelsByUser | p99 | 1.168s | 879ms | -289ms | -24.74
| FileInfoStore.GetByIds | p99 | 1.942s | 1.517s | -425ms | -21.88
| ChannelStore.GetPinnedPostCount | p99 | 1.387s | 1.086s | -301ms | -21.70
| PluginStore.Delete | p99 | 37ms | 29ms | -8ms | -21.35
| UserStore.Get | p99 | 775ms | 617ms | -158ms | -20.38
| UserStore.UpdateLastLogin | p99 | 62ms | 50ms | -12ms | -19.48
| PostStore.Update | p99 | 234ms | 190ms | -44ms | -18.80
| PostStore.SearchPostsForUser | p99 | 2.254s | 1.84s | -414ms | -18.37
| UserStore.IsEmpty | p99 | 580ms | 475ms | -105ms | -18.09
| GroupStore.GetByName | p99 | 744ms | 617ms | -127ms | -17.08
| AuditStore.Save | p99 | 66ms | 55ms | -11ms | -16.60
| ChannelStore.GetAllChannelMembersForUser | p99 | 833ms | 703ms | -130ms | -15.60
| UserStore.Search | p99 | 2.375s | 2.024s | -351ms | -14.78
| UserStore.UpdateFailedPasswordAttempts | p99 | 66ms | 57ms | -9ms | -13.58
| ThreadStore.GetMembershipForUser | p99 | 1.334s | 1.162s | -172ms | -12.89
| TeamStore.GetTeamsForUser | p99 | 718ms | 626ms | -92ms | -12.81
| JobStore.GetAllByTypePage | p99 | 1.98s | 1.735s | -245ms | -12.37
| PostPersistentNotificationStore.Get | p99 | 90ms | 79ms | -11ms | -12.22
| ChannelStore.GetMembersForUser | p99 | 1.135s | 998ms | -137ms | -12.07
| ThreadStore.MarkAllAsReadByChannels | p99 | 86ms | 76ms | -10ms | -11.63
| SessionStore.Save | p99 | 847ms | 755ms | -92ms | -10.86
| StatusStore.GetByIds | p99 | 1.801s | 1.615s | -186ms | -10.33
| FileInfoStore.AttachToPost | p99 | 81ms | 73ms | -8ms | -9.92
| ChannelStore.GetFileCount | p99 | 961ms | 866ms | -95ms | -9.89
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 51ms | 47ms | -4ms | -7.77
| ProductNoticesStore.View | p99 | 337ms | 311ms | -26ms | -7.72
| JobStore.Save | p99 | 67ms | 62ms | -5ms | -7.46
| PluginStore.SetWithOptions | p99 | 83ms | 77ms | -6ms | -7.21
| StatusStore.Get | p99 | 845ms | 785ms | -60ms | -7.10
| PostStore.GetPostsSince | p99 | 1.484s | 1.38s | -104ms | -7.01
| ChannelStore.UpdateLastViewedAt | p99 | 107ms | 100ms | -7ms | -6.53
| StatusStore.UpdateLastActivityAt | p99 | 78ms | 73ms | -5ms | -6.39
| ChannelStore.GetChannels | p99 | 1.058s | 991ms | -67ms | -6.33
| ChannelStore.SaveMember | p99 | 2.663s | 2.498s | -165ms | -6.20
| SessionStore.GetLRUSessions | p99 | 852ms | 801ms | -51ms | -5.99
| UserStore.Count | p99 | 986ms | 932ms | -54ms | -5.48
| FileInfoStore.GetForPost | p99 | 1.678s | 1.592s | -86ms | -5.12
| ThreadStore.GetThreadForUser | p99 | 2.067s | 1.965s | -102ms | -4.93
| PostPersistentNotificationStore.GetSingle | p99 | 1.378s | 1.313s | -65ms | -4.72
| PostStore.GetSingle | p99 | 1.268s | 1.214s | -54ms | -4.26
| ThreadStore.GetThreadFollowers | p99 | 1.318s | 1.265s | -53ms | -4.02
| SessionStore.UpdateLastActivityAt | p99 | 51ms | 49ms | -2ms | -3.90
| FileInfoStore.Get | p99 | 896ms | 862ms | -34ms | -3.79
| ThreadStore.MaintainMembership | p99 | 161ms | 155ms | -6ms | -3.72
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 954ms | 919ms | -35ms | -3.67
| TeamStore.Get | p99 | 1.179s | 1.137s | -42ms | -3.56
| PreferenceStore.Get | p99 | 1.03s | 994ms | -36ms | -3.50
| LinkMetadataStore.Get | p99 | 1.316s | 1.271s | -45ms | -3.42
| UserStore.GetProfilesByUsernames | p99 | 917ms | 887ms | -30ms | -3.27
| ChannelStore.GetMemberLastViewedAt | p99 | 868ms | 845ms | -23ms | -2.65
| ThreadStore.GetTotalThreads | p99 | 935ms | 912ms | -23ms | -2.46
| UserStore.GetByUsername | p99 | 998ms | 974ms | -24ms | -2.40
| JobStore.UpdateOptimistically | p99 | 93ms | 91ms | -2ms | -2.16
| UserStore.GetForLogin | p99 | 805ms | 789ms | -16ms | -1.99
| PostStore.GetPostsBefore | p99 | 1.009s | 989ms | -20ms | -1.98
| ChannelStore.GetGuestCount | p99 | 984ms | 967ms | -17ms | -1.73
| ThreadStore.GetTeamsUnreadForUser | p99 | 1.665s | 1.637s | -28ms | -1.68
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 924ms | 909ms | -15ms | -1.62
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 894ms | 881ms | -13ms | -1.45
| TeamStore.GetActiveMemberCount | p99 | 990ms | 977ms | -13ms | -1.31
| JobStore.GetAllByStatus | p99 | 978ms | 966ms | -12ms | -1.23
| UserStore.Save | p99 | 248ms | 245ms | -3ms | -1.21
| SessionStore.Get | p99 | 895ms | 885ms | -10ms | -1.12
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 19ms | 165ms | 146ms | 754.41
| getChannelMembersForUser | avg | 210ms | 1.588s | 1.378s | 656.91
| listChannelBookmarksForChannel | avg | 104ms | 476ms | 372ms | 359.18
| getPrevTrialLicense | avg | 94ms | 336ms | 242ms | 258.15
| createCategoryForTeamForUser | avg | 246ms | 435ms | 189ms | 76.75
| getGroups | avg | 272ms | 453ms | 181ms | 66.46
| deletePost | avg | 459ms | 737ms | 278ms | 60.60
| getChannelMembers | avg | 73ms | 86ms | 13ms | 17.92
| getUser | avg | 141ms | 147ms | 6ms | 4.25
| getPreferences | avg | 149ms | 155ms | 6ms | 4.03
| addChannelMember | avg | 1.806s | 1.848s | 42ms | 2.33
| uploadFileStream | avg | 410ms | 419ms | 9ms | 2.19
| getTeamsForUser | avg | 104ms | 106ms | 2ms | 1.92
| updateCategoriesForTeamForUser | avg | 746ms | 759ms | 13ms | 1.74
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembersForUser | p99 | 492ms | 4.9s | 4.408s | 895.03
| getRolesByNames | p99 | 241ms | 2.365s | 2.124s | 881.32
| deletePost | p99 | 991ms | 4.837s | 3.846s | 388.27
| listChannelBookmarksForChannel | p99 | 925ms | 2.431s | 1.506s | 162.81
| createCategoryForTeamForUser | p99 | 490ms | 990ms | 500ms | 102.04
| getPrevTrialLicense | p99 | 493ms | 985ms | 492ms | 99.90
| getGroups | p99 | 495ms | 985ms | 490ms | 98.99
| searchGroupChannels | p99 | 997ms | 1.524s | 527ms | 52.86
| searchPostsInTeam | p99 | 4.859s | 6.782s | 1.923s | 39.58
| saveReaction | p99 | 2.483s | 3.265s | 782ms | 31.49
| getUserStatusesByIds | p99 | 8ms | 10ms | 2ms | 23.73
| getChannelMember | p99 | 1.192s | 1.47s | 278ms | 23.32
| getUser | p99 | 1.048s | 1.193s | 145ms | 13.83
| updateReadStateThreadByUser | p99 | 6.79s | 7.543s | 753ms | 11.09
| getUsers | p99 | 627ms | 686ms | 59ms | 9.41
| unfollowThreadByUser | p99 | 2.234s | 2.444s | 210ms | 9.40
| addChannelMember | p99 | 9.187s | 9.6s | 413ms | 4.50
| deleteDraft | p99 | 1.616s | 1.65s | 34ms | 2.10
| getTeamsForUser | p99 | 876ms | 894ms | 18ms | 2.06
| getProfileImage | p99 | 464ms | 472ms | 8ms | 1.72
| getChannelMembers | p99 | 242ms | 246ms | 4ms | 1.65
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 137ms | 0s | -137ms | -100.31
| searchFiles | avg | 444ms | 0s | -444ms | -99.91
| channelMemberCountsByGroup | avg | 7ms | 0s | -7ms | -94.76
| updateReadStateAllThreadsByUser | avg | 9ms | 2ms | -7ms | -77.08
| followThreadByUser | avg | 392ms | 123ms | -269ms | -68.69
| patchPost | avg | 2.128s | 1.122s | -1.006s | -47.26
| getChannelUnread | avg | 144ms | 76ms | -68ms | -47.13
| setPostReminder | avg | 759ms | 419ms | -340ms | -44.80
| createChannel | avg | 2.03s | 1.16s | -870ms | -42.85
| getAnalytics | avg | 1.318s | 808ms | -510ms | -38.69
| createPost | avg | 4.183s | 2.672s | -1.511s | -36.13
| searchAllChannels | avg | 4.699s | 3.166s | -1.533s | -32.62
| getChannelsForUser | avg | 138ms | 101ms | -37ms | -26.84
| logout | avg | 278ms | 205ms | -73ms | -26.22
| getChannelStats | avg | 142ms | 106ms | -36ms | -25.43
| getFilteredUsersStats | avg | 327ms | 246ms | -81ms | -24.79
| getChannel | avg | 303ms | 229ms | -74ms | -24.45
| login | avg | 382ms | 304ms | -78ms | -20.41
| getTeamStats | avg | 546ms | 437ms | -109ms | -19.96
| getJobsByType | avg | 176ms | 142ms | -34ms | -19.36
| autocompleteChannelsForTeamForSearch | avg | 617ms | 498ms | -119ms | -19.29
| searchUsers | avg | 418ms | 340ms | -78ms | -18.66
| getDrafts | avg | 178ms | 145ms | -33ms | -18.50
| getTeamMembersForUser | avg | 92ms | 75ms | -17ms | -18.39
| getUsersByNames | avg | 116ms | 95ms | -21ms | -18.15
| autocompleteUsers | avg | 703ms | 579ms | -124ms | -17.64
| getPostsForChannel | avg | 1.494s | 1.231s | -263ms | -17.60
| getTeamMember | avg | 12ms | 10ms | -2ms | -17.32
| getUsersByIds | avg | 12ms | 10ms | -2ms | -16.58
| getFileThumbnail | avg | 166ms | 139ms | -27ms | -16.24
| getPostThread | avg | 860ms | 722ms | -138ms | -16.05
| searchPostsInTeam | avg | 550ms | 464ms | -86ms | -15.63
| createDirectChannel | avg | 914ms | 777ms | -137ms | -14.99
| updateReadStateThreadByUser | avg | 1.257s | 1.07s | -187ms | -14.87
| viewChannel | avg | 285ms | 246ms | -39ms | -13.66
| createGroupChannel | avg | 2.399s | 2.074s | -325ms | -13.54
| getFilePreview | avg | 173ms | 150ms | -23ms | -13.29
| getChannelMembersForTeamForUser | avg | 140ms | 123ms | -17ms | -12.13
| getThreadsForUser | avg | 170ms | 150ms | -20ms | -11.77
| deleteDraft | avg | 172ms | 153ms | -19ms | -11.07
| getChannelsForTeamForUser | avg | 140ms | 126ms | -14ms | -10.03
| unfollowThreadByUser | avg | 327ms | 297ms | -30ms | -9.17
| getClientConfig | avg | 23ms | 21ms | -2ms | -8.69
| searchGroupChannels | avg | 163ms | 149ms | -14ms | -8.59
| getCategoriesForTeamForUser | avg | 268ms | 245ms | -23ms | -8.59
| saveReaction | avg | 460ms | 423ms | -37ms | -8.04
| upsertDraft | avg | 64ms | 59ms | -5ms | -7.80
| getPostsForChannelAroundLastUnread | avg | 509ms | 471ms | -38ms | -7.46
| addTeamMember | avg | 3.63s | 3.392s | -238ms | -6.56
| getPublicChannelsForTeam | avg | 197ms | 185ms | -12ms | -6.10
| getProfileImage | avg | 91ms | 86ms | -5ms | -5.51
| getTeamsUnreadForUser | avg | 170ms | 162ms | -8ms | -4.71
| createUser | avg | 315ms | 307ms | -8ms | -2.54
| removeUserCustomStatus | avg | 199ms | 195ms | -4ms | -2.01
| getAllTeams | avg | 113ms | 111ms | -2ms | -1.76
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 249ms | 0s | -249ms | -100.20
| searchFiles | p99 | 498ms | 0s | -498ms | -100.05
| channelMemberCountsByGroup | p99 | 88ms | 0s | -88ms | -100.00
| followThreadByUser | p99 | 4.575s | 488ms | -4.087s | -89.34
| updateReadStateAllThreadsByUser | p99 | 25ms | 5ms | -20ms | -80.97
| getAnalytics | p99 | 2.47s | 995ms | -1.475s | -59.72
| patchPost | p99 | 10s | 4.836s | -5.164s | -51.64
| createChannel | p99 | 9.55s | 4.775s | -4.775s | -50.00
| getPublicChannelsForTeam | p99 | 1.915s | 989ms | -926ms | -48.35
| setPostReminder | p99 | 4.425s | 2.41s | -2.015s | -45.54
| getDrafts | p99 | 1.894s | 1.046s | -848ms | -44.78
| getChannelUnread | p99 | 1.522s | 861ms | -661ms | -43.43
| autocompleteChannelsForTeamForSearch | p99 | 4.019s | 2.477s | -1.542s | -38.37
| autocompleteUsers | p99 | 3.956s | 2.446s | -1.51s | -38.17
| getChannelsForUser | p99 | 1.202s | 890ms | -312ms | -25.96
| getChannelStats | p99 | 2.234s | 1.878s | -356ms | -15.93
| getUsersByIds | p99 | 295ms | 248ms | -47ms | -15.93
| searchUsers | p99 | 2.38s | 2.03s | -350ms | -14.70
| getFileThumbnail | p99 | 1.229s | 1.053s | -176ms | -14.32
| uploadFileStream | p99 | 1.287s | 1.123s | -164ms | -12.74
| getJobsByType | p99 | 1.985s | 1.735s | -250ms | -12.59
| getChannelMembersForTeamForUser | p99 | 1.106s | 998ms | -108ms | -9.76
| updateCategoriesForTeamForUser | p99 | 4.3s | 3.9s | -400ms | -9.30
| getTeamMembersForUser | p99 | 805ms | 738ms | -67ms | -8.33
| getFilePreview | p99 | 1.081s | 994ms | -87ms | -8.05
| getTeamMember | p99 | 244ms | 225ms | -19ms | -7.78
| createUser | p99 | 2.148s | 1.987s | -161ms | -7.50
| createDirectChannel | p99 | 4.458s | 4.125s | -333ms | -7.47
| removeUserCustomStatus | p99 | 1.045s | 984ms | -61ms | -5.84
| getClientConfig | p99 | 405ms | 386ms | -19ms | -4.69
| getUsersByNames | p99 | 926ms | 896ms | -30ms | -3.24
| login | p99 | 2.461s | 2.387s | -74ms | -3.01
| getChannelsForTeamForUser | p99 | 1.019s | 992ms | -27ms | -2.65
| getChannel | p99 | 2.39s | 2.338s | -52ms | -2.18
| createGroupChannel | p99 | 10s | 9.86s | -140ms | -1.40
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 66ms| 55ms | -11ms | -16.601
| BotStore.Get |  Avg| 136ms| 111ms | -25ms | -18.342
| |  P99| 937ms| 468ms | -469ms | -50.027
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 38ms| 202ms | 164ms | 434.591
| |  P99| 228ms| 943ms | 715ms | 313.959
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 790ms| 637ms | -153ms | -19.365
| |  P99| 2.49s| 2.474s | -16ms | -0.643
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.049
| ChannelStore.AnalyticsTypeCount |  Avg| 69ms| 78ms | 9ms | 13.096
| |  P99| 247ms| 100ms | -147ms | -59.514
| ChannelStore.Autocomplete |  Avg| 4.691s| 3.164s | -1.527s | -32.551
| |  P99| 10s| 10s | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 617ms| 498ms | -119ms | -19.293
| |  P99| 4.019s| 2.476s | -1.543s | -38.395
| ChannelStore.CreateDirectChannel |  Avg| 483ms| 338ms | -145ms | -30.043
| |  P99| 2.437s| 2.45s | 13ms | 0.533
| ChannelStore.CreateInitialSidebarCategories |  Avg| 111ms| 111ms | 0s | 0.000
| |  P99| 878ms| 900ms | 22ms | 2.505
| ChannelStore.CreateSidebarCategory |  Avg| 72ms| 241ms | 169ms | 235.018
| |  P99| 247ms| 495ms | 248ms | 100.405
| ChannelStore.Get |  Avg| 185ms| 184ms | -1ms | -0.540
| |  P99| 1.487s| 1.637s | 150ms | 10.087
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 183ms| 152ms | -31ms | -16.977
| |  P99| 1.473s| 1.78s | 307ms | 20.849
| ChannelStore.GetAllChannelMembersForUser |  Avg| 106ms| 70ms | -36ms | -33.887
| |  P99| 833ms| 703ms | -130ms | -15.603
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 145ms| 163ms | 18ms | 12.402
| |  P99| 889ms| 979ms | 90ms | 10.118
| ChannelStore.GetByName |  Avg| 99ms| 97ms | -2ms | -2.020
| |  P99| 878ms| 883ms | 5ms | 0.569
| ChannelStore.GetByNameIncludeDeleted |  Avg| 131ms| 40ms | -91ms | -69.412
| |  P99| 249ms| 50ms | -199ms | -80.033
| ChannelStore.GetChannelUnread |  Avg| 134ms| 75ms | -59ms | -44.014
| |  P99| 1.359s| 856ms | -503ms | -37.008
| ChannelStore.GetChannels |  Avg| 142ms| 125ms | -17ms | -11.967
| |  P99| 1.058s| 991ms | -67ms | -6.331
| ChannelStore.GetChannelsByUser |  Avg| 138ms| 101ms | -37ms | -26.908
| |  P99| 1.168s| 879ms | -289ms | -24.739
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 130ms| 111ms | -19ms | -14.645
| |  P99| 979ms| 978ms | -1ms | -0.102
| ChannelStore.GetFileCount |  Avg| 111ms| 89ms | -22ms | -19.799
| |  P99| 961ms| 866ms | -95ms | -9.890
| ChannelStore.GetGuestCount |  Avg| 141ms| 133ms | -8ms | -5.682
| |  P99| 984ms| 967ms | -17ms | -1.727
| ChannelStore.GetMember |  Avg| 6ms| 7ms | 1ms | 16.786
| |  P99| 108ms| 157ms | 49ms | 45.210
| ChannelStore.GetMemberCount |  Avg| 573ms| 477ms | -96ms | -16.749
| |  P99| 3.37s| 2.275s | -1.095s | -32.489
| ChannelStore.GetMemberCountsByGroup |  Avg| 7ms| 0s | -7ms | -99.285
| |  P99| 88ms| 0s | -88ms | -99.999
| ChannelStore.GetMemberForPost |  Avg| 167ms| 150ms | -17ms | -10.181
| |  P99| 1.54s| 1.567s | 27ms | 1.753
| ChannelStore.GetMemberLastViewedAt |  Avg| 98ms| 89ms | -9ms | -9.157
| |  P99| 868ms| 845ms | -23ms | -2.651
| ChannelStore.GetMembers |  Avg| 72ms| 85ms | 13ms | 18.050
| |  P99| 242ms| 246ms | 4ms | 1.649
| ChannelStore.GetMembersForUser |  Avg| 142ms| 123ms | -19ms | -13.359
| |  P99| 1.135s| 998ms | -137ms | -12.071
| ChannelStore.GetMembersForUserWithPagination |  Avg| 167ms| 977ms | 810ms | 486.031
| |  P99| 487ms| 4.875s | 4.388s | 900.104
| ChannelStore.GetPinnedPostCount |  Avg| 159ms| 115ms | -44ms | -27.653
| |  P99| 1.387s| 1.086s | -301ms | -21.701
| ChannelStore.GetPublicChannelsForTeam |  Avg| 195ms| 184ms | -11ms | -5.640
| |  P99| 1.915s| 989ms | -926ms | -48.355
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 267ms| 245ms | -22ms | -8.225
| |  P99| 2.241s| 2.25s | 9ms | 0.402
| ChannelStore.GetSidebarCategory |  Avg| 138ms| 146ms | 8ms | 5.792
| |  P99| 1.69s| 857ms | -833ms | -49.291
| ChannelStore.GetTeamChannels |  Avg| 282ms| 184ms | -98ms | -34.758
| |  P99| 955ms| 489ms | -466ms | -48.795
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Save |  Avg| 193ms| 168ms | -25ms | -12.942
| |  P99| 996ms| 1.458s | 462ms | 46.380
| ChannelStore.SaveMember |  Avg| 436ms| 418ms | -18ms | -4.130
| |  P99| 2.663s| 2.498s | -165ms | -6.196
| ChannelStore.SearchGroupChannels |  Avg| 163ms| 149ms | -14ms | -8.597
| |  P99| 997ms| 1.524s | 527ms | 52.859
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 107ms| 100ms | -7ms | -6.527
| ChannelStore.UpdateSidebarCategories |  Avg| 255ms| 290ms | 35ms | 13.700
| |  P99| 2.08s| 2.163s | 83ms | 3.990
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 51ms| 47ms | -4ms | -7.772
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 7ms| 5ms | -2ms | -28.350
| |  P99| 82ms| 57ms | -25ms | -30.541
| CommandWebhookStore.Cleanup |  Avg| 7ms| 27ms | 20ms | 296.541
| |  P99| 24ms| 98ms | 74ms | 303.276
| ComplianceStore.MessageExport |  Avg| 115ms| 81ms | -34ms | -29.452
| |  P99| 939ms| 1.734s | 795ms | 84.695
| DraftStore.Delete |  Avg| 5ms| 6ms | 1ms | 18.262
| |  P99| 71ms| 73ms | 2ms | 2.806
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 26ms| 21ms | -5ms | -19.244
| |  P99| 91ms| 49ms | -42ms | -45.902
| DraftStore.Get |  Avg| 171ms| 153ms | -18ms | -10.512
| |  P99| 1.616s| 1.65s | 34ms | 2.104
| DraftStore.GetDraftsForUser |  Avg| 172ms| 142ms | -30ms | -17.470
| |  P99| 1.736s| 1.045s | -691ms | -39.809
| DraftStore.Upsert |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 76ms| 79ms | 3ms | 3.950
| EmojiStore.GetByName |  Avg| 147ms| 133ms | -14ms | -9.550
| |  P99| 1.121s| 1.151s | 30ms | 2.675
| EmojiStore.GetMultipleByName |  Avg| 98ms| 246ms | 148ms | 150.730
| |  P99| 247ms| 2.17s | 1.923s | 777.952
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -15.284
| |  P99| 81ms| 73ms | -8ms | -9.915
| FileInfoStore.Get |  Avg| 105ms| 83ms | -22ms | -20.919
| |  P99| 896ms| 862ms | -34ms | -3.793
| FileInfoStore.GetByIds |  Avg| 195ms| 138ms | -57ms | -29.276
| |  P99| 1.942s| 1.517s | -425ms | -21.880
| FileInfoStore.GetForPost |  Avg| 169ms| 146ms | -23ms | -13.588
| |  P99| 1.678s| 1.592s | -86ms | -5.124
| FileInfoStore.Save |  Avg| 7ms| 6ms | -1ms | -15.307
| |  P99| 75ms| 77ms | 2ms | 2.682
| FileInfoStore.Search |  Avg| 299ms| 0s | -299ms | -100.027
| |  P99| 497ms| 0s | -497ms | -99.899
| FileInfoStore.SetContent |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 117ms | 19ms | 19.388
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 105ms| 100ms | -5ms | -4.782
| |  P99| 853ms| 847ms | -6ms | -0.704
| GroupStore.GetByName |  Avg| 81ms| 75ms | -6ms | -7.426
| |  P99| 744ms| 617ms | -127ms | -17.079
| GroupStore.GetGroups |  Avg| 142ms| 129ms | -13ms | -9.158
| |  P99| 1.163s| 1.318s | 155ms | 13.324
| JobStore.Get |  Avg| 169ms| 129ms | -40ms | -23.654
| |  P99| 1.594s| 1.785s | 191ms | 11.986
| JobStore.GetAllByStatus |  Avg| 132ms| 127ms | -5ms | -3.784
| |  P99| 978ms| 966ms | -12ms | -1.227
| JobStore.GetAllByTypePage |  Avg| 176ms| 142ms | -34ms | -19.346
| |  P99| 1.98s| 1.735s | -245ms | -12.374
| JobStore.GetCountByStatusAndType |  Avg| 103ms| 123ms | 20ms | 19.502
| |  P99| 610ms| 1.36s | 750ms | 122.951
| JobStore.GetNewestJobByStatusesAndType |  Avg| 122ms| 120ms | -2ms | -1.638
| |  P99| 770ms| 1.353s | 583ms | 75.714
| JobStore.Save |  Avg| 6ms| 4ms | -2ms | -32.635
| |  P99| 67ms| 62ms | -5ms | -7.463
| JobStore.UpdateOptimistically |  Avg| 7ms| 6ms | -1ms | -14.649
| |  P99| 93ms| 91ms | -2ms | -2.160
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 7ms | 1ms | 16.992
| |  P99| 67ms| 137ms | 70ms | 104.485
| LicenseStore.GetAll |  Avg| 301ms| 280ms | -21ms | -6.986
| |  P99| 980ms| 980ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 146ms| 124ms | -22ms | -15.020
| |  P99| 1.316s| 1.271s | -45ms | -3.419
| LinkMetadataStore.Save |  Avg| 8ms| 5ms | -3ms | -39.277
| |  P99| 149ms| 53ms | -96ms | -64.218
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 37ms| 29ms | -8ms | -21.353
| PluginStore.Get |  Avg| 99ms| 591ms | 492ms | 498.118
| |  P99| 247ms| 4.85s | 4.603s | 1863.563
| PluginStore.List |  Avg| 158ms| 98ms | -60ms | -37.929
| |  P99| 1.75s| 730ms | -1.02s | -58.294
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 83ms| 77ms | -6ms | -7.214
| PostAcknowledgementStore.GetForPost |  Avg| 136ms| 105ms | -31ms | -22.766
| |  P99| 876ms| 941ms | 65ms | 7.417
| PostAcknowledgementStore.GetForPosts |  Avg| 231ms| 196ms | -35ms | -15.122
| |  P99| 2.299s| 2.279s | -20ms | -0.870
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 6ms | 3ms | 102.377
| |  P99| 80ms| 89ms | 9ms | 11.250
| PostPersistentNotificationStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 90ms| 79ms | -11ms | -12.222
| PostPersistentNotificationStore.GetSingle |  Avg| 156ms| 137ms | -19ms | -12.196
| |  P99| 1.378s| 1.313s | -65ms | -4.718
| PostPriorityStore.GetForPost |  Avg| 124ms| 106ms | -18ms | -14.481
| |  P99| 910ms| 1.085s | 175ms | 19.231
| PostPriorityStore.GetForPosts |  Avg| 237ms| 202ms | -35ms | -14.789
| |  P99| 2.312s| 2.295s | -17ms | -0.735
| PostStore.AnalyticsPostCount |  Avg| 2.699s| 1.803s | -896ms | -33.196
| |  P99| 9.9s| 4.925s | -4.975s | -50.253
| PostStore.Delete |  Avg| 159ms| 192ms | 33ms | 20.753
| |  P99| 489ms| 967ms | 478ms | 97.676
| PostStore.Get |  Avg| 243ms| 211ms | -32ms | -13.191
| |  P99| 2.118s| 2.174s | 56ms | 2.643
| PostStore.GetEtag |  Avg| 142ms| 130ms | -12ms | -8.446
| |  P99| 1s| 996ms | -4ms | -0.400
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 51ms| 54ms | 3ms | 5.869
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 70ms| 69ms | -1ms | -1.432
| PostStore.GetPostReminderMetadata |  Avg| 182ms| 80ms | -102ms | -56.193
| |  P99| 1.84s| 472ms | -1.368s | -74.346
| PostStore.GetPostReminders |  Avg| 17ms| 4ms | -13ms | -74.948
| |  P99| 213ms| 23ms | -190ms | -89.412
| PostStore.GetPosts |  Avg| 97ms| 91ms | -6ms | -6.171
| |  P99| 832ms| 825ms | -7ms | -0.841
| PostStore.GetPostsAfter |  Avg| 117ms| 90ms | -27ms | -23.075
| |  P99| 1.405s| 954ms | -451ms | -32.099
| PostStore.GetPostsBefore |  Avg| 145ms| 122ms | -23ms | -15.873
| |  P99| 1.009s| 989ms | -20ms | -1.982
| PostStore.GetPostsByThread |  Avg| 149ms| 127ms | -22ms | -14.808
| |  P99| 1.308s| 1.464s | 156ms | 11.927
| PostStore.GetPostsSince |  Avg| 196ms| 164ms | -32ms | -16.300
| |  P99| 1.484s| 1.38s | -104ms | -7.007
| PostStore.GetSingle |  Avg| 144ms| 121ms | -23ms | -15.968
| |  P99| 1.268s| 1.214s | -54ms | -4.258
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 197ms| 196ms | -1ms | -0.508
| PostStore.SearchPostsForUser |  Avg| 288ms| 215ms | -73ms | -25.331
| |  P99| 2.254s| 1.84s | -414ms | -18.371
| PostStore.SetPostReminder |  Avg| 9ms| 23ms | 14ms | 157.487
| |  P99| 47ms| 236ms | 189ms | 401.061
| PostStore.Update |  Avg| 21ms| 19ms | -2ms | -9.373
| |  P99| 234ms| 190ms | -44ms | -18.804
| PreferenceStore.DeleteCategoryAndName |  Avg| 9ms| 3ms | -6ms | -67.107
| |  P99| 91ms| 23ms | -68ms | -74.317
| PreferenceStore.Get |  Avg| 138ms| 119ms | -19ms | -13.754
| |  P99| 1.03s| 994ms | -36ms | -3.496
| PreferenceStore.GetAll |  Avg| 146ms| 152ms | 6ms | 4.120
| |  P99| 1.112s| 1.145s | 33ms | 2.968
| PreferenceStore.Save |  Avg| 12ms| 11ms | -1ms | -8.368
| |  P99| 177ms| 178ms | 1ms | 0.565
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 136ms| 208ms | 72ms | 52.880
| |  P99| 249ms| 249ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 34ms| 32ms | -2ms | -5.910
| |  P99| 337ms| 311ms | -26ms | -7.717
| ReactionStore.GetForPost |  Avg| 139ms| 130ms | -9ms | -6.485
| |  P99| 973ms| 1.037s | 64ms | 6.579
| RetentionPolicyStore.GetAll |  Avg| 17ms| 266ms | 249ms | 1444.378
| |  P99| 25ms| 498ms | 473ms | 1903.421
| RetentionPolicyStore.GetCount |  Avg| 8ms| 150ms | 142ms | 1711.947
| |  P99| 10ms| 247ms | 237ms | 2381.910
| RoleStore.ChannelHigherScopedPermissions |  Avg| 108ms| 109ms | 1ms | 0.927
| |  P99| 902ms| 1.754s | 852ms | 94.494
| RoleStore.GetByNames |  Avg| 142ms| 152ms | 10ms | 7.061
| |  P99| 852ms| 1.053s | 201ms | 23.599
| SessionStore.Get |  Avg| 108ms| 101ms | -7ms | -6.495
| |  P99| 895ms| 885ms | -10ms | -1.118
| SessionStore.GetLRUSessions |  Avg| 99ms| 86ms | -13ms | -13.130
| |  P99| 852ms| 801ms | -51ms | -5.987
| SessionStore.GetSessionsExpired |  Avg| 99ms| 137ms | 38ms | 38.398
| |  P99| 478ms| 945ms | 467ms | 97.801
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 116ms| 99ms | -17ms | -14.602
| |  P99| 954ms| 919ms | -35ms | -3.670
| SessionStore.Remove |  Avg| 5ms| 7ms | 2ms | 40.407
| |  P99| 46ms| 86ms | 40ms | 86.958
| SessionStore.Save |  Avg| 102ms| 86ms | -16ms | -15.756
| |  P99| 847ms| 755ms | -92ms | -10.862
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 51ms| 49ms | -2ms | -3.904
| StatusStore.Get |  Avg| 84ms| 78ms | -6ms | -7.131
| |  P99| 845ms| 785ms | -60ms | -7.097
| StatusStore.GetByIds |  Avg| 181ms| 153ms | -28ms | -15.512
| |  P99| 1.801s| 1.615s | -186ms | -10.326
| StatusStore.SaveOrUpdate |  Avg| 13ms| 14ms | 1ms | 7.965
| |  P99| 224ms| 224ms | 0s | 0.000
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 6ms | -2ms | -25.845
| |  P99| 88ms| 87ms | -1ms | -1.143
| StatusStore.UpdateLastActivityAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 78ms| 73ms | -5ms | -6.393
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.171
| TeamStore.AnalyticsTeamCount |  Avg| 70ms| 62ms | -8ms | -11.465
| |  P99| 247ms| 99ms | -148ms | -59.919
| TeamStore.Get |  Avg| 139ms| 119ms | -20ms | -14.355
| |  P99| 1.179s| 1.137s | -42ms | -3.563
| TeamStore.GetActiveMemberCount |  Avg| 546ms| 390ms | -156ms | -28.595
| |  P99| 990ms| 977ms | -13ms | -1.313
| TeamStore.GetAllPage |  Avg| 107ms| 105ms | -2ms | -1.874
| |  P99| 884ms| 888ms | 4ms | 0.452
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 106ms| 100ms | -6ms | -5.667
| |  P99| 894ms| 881ms | -13ms | -1.454
| TeamStore.GetMember |  Avg| 7ms| 5ms | -2ms | -27.720
| |  P99| 199ms| 130ms | -69ms | -34.631
| TeamStore.GetTeamsByUserId |  Avg| 104ms| 105ms | 1ms | 0.963
| |  P99| 875ms| 894ms | 19ms | 2.170
| TeamStore.GetTeamsForUser |  Avg| 85ms| 69ms | -16ms | -18.846
| |  P99| 718ms| 626ms | -92ms | -12.808
| TeamStore.GetTotalMemberCount |  Avg| 399ms| 365ms | -34ms | -8.511
| |  P99| 960ms| 977ms | 17ms | 1.771
| TeamStore.SaveMember |  Avg| 205ms| 206ms | 1ms | 0.489
| |  P99| 956ms| 958ms | 2ms | 0.209
| ThreadStore.Get |  Avg| 178ms| 135ms | -43ms | -24.191
| |  P99| 2.75s| 948ms | -1.802s | -65.530
| ThreadStore.GetMembershipForUser |  Avg| 149ms| 126ms | -23ms | -15.469
| |  P99| 1.334s| 1.162s | -172ms | -12.891
| ThreadStore.GetTeamsUnreadForUser |  Avg| 143ms| 129ms | -14ms | -9.771
| |  P99| 1.665s| 1.637s | -28ms | -1.682
| ThreadStore.GetThreadFollowers |  Avg| 151ms| 133ms | -18ms | -11.947
| |  P99| 1.318s| 1.265s | -53ms | -4.022
| ThreadStore.GetThreadForUser |  Avg| 225ms| 185ms | -40ms | -17.751
| |  P99| 2.067s| 1.965s | -102ms | -4.935
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 153ms| 130ms | -23ms | -15.054
| |  P99| 1.282s| 1.417s | 135ms | 10.527
| ThreadStore.GetThreadsForUser |  Avg| 165ms| 146ms | -19ms | -11.525
| |  P99| 1.381s| 1.467s | 86ms | 6.228
| ThreadStore.GetTotalThreads |  Avg| 114ms| 102ms | -12ms | -10.487
| |  P99| 935ms| 912ms | -23ms | -2.459
| ThreadStore.GetTotalUnreadMentions |  Avg| 112ms| 102ms | -10ms | -8.931
| |  P99| 933ms| 932ms | -1ms | -0.107
| ThreadStore.GetTotalUnreadThreads |  Avg| 110ms| 102ms | -8ms | -7.289
| |  P99| 914ms| 910ms | -4ms | -0.438
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 112ms| 102ms | -10ms | -8.941
| |  P99| 924ms| 909ms | -15ms | -1.623
| ThreadStore.MaintainMembership |  Avg| 10ms| 9ms | -1ms | -10.217
| |  P99| 161ms| 155ms | -6ms | -3.717
| ThreadStore.MarkAllAsReadByChannels |  Avg| 6ms| 4ms | -2ms | -35.950
| |  P99| 86ms| 76ms | -10ms | -11.633
| ThreadStore.MarkAllAsReadByTeam |  Avg| 9ms| 2ms | -7ms | -78.361
| |  P99| 25ms| 5ms | -20ms | -80.972
| ThreadStore.MarkAsRead |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 65ms| 65ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 82ms| 81ms | -1ms | -1.223
| TokenStore.Cleanup |  Avg| 7ms| 30ms | 23ms | 343.199
| |  P99| 24ms| 98ms | 74ms | 303.276
| UserAccessTokenStore.GetByToken |  Avg| 17ms| 36ms | 19ms | 109.529
| |  P99| 244ms| 595ms | 351ms | 143.852
| UserStore.AnalyticsActiveCount |  Avg| 671ms| 462ms | -209ms | -31.154
| |  P99| 994ms| 990ms | -4ms | -0.402
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 76ms| 61ms | -15ms | -19.865
| |  P99| 247ms| 99ms | -148ms | -59.919
| UserStore.AutocompleteUsersInChannel |  Avg| 793ms| 656ms | -137ms | -17.272
| |  P99| 4.153s| 2.459s | -1.694s | -40.791
| UserStore.Count |  Avg| 447ms| 292ms | -155ms | -34.689
| |  P99| 986ms| 932ms | -54ms | -5.475
| UserStore.Get |  Avg| 65ms| 48ms | -17ms | -26.168
| |  P99| 775ms| 617ms | -158ms | -20.382
| UserStore.GetAllProfiles |  Avg| 80ms| 80ms | 0s | 0.000
| |  P99| 781ms| 846ms | 65ms | 8.324
| UserStore.GetAllProfilesInChannel |  Avg| 1.325s| 1.099s | -226ms | -17.053
| |  P99| 7.496s| 3.602s | -3.894s | -51.944
| UserStore.GetByUsername |  Avg| 137ms| 136ms | -1ms | -0.728
| |  P99| 998ms| 974ms | -24ms | -2.405
| UserStore.GetForLogin |  Avg| 93ms| 86ms | -7ms | -7.510
| |  P99| 805ms| 789ms | -16ms | -1.987
| UserStore.GetMany |  Avg| 200ms| 142ms | -58ms | -29.051
| |  P99| 2.155s| 905ms | -1.25s | -58.005
| UserStore.GetProfileByIds |  Avg| 79ms| 74ms | -5ms | -6.333
| |  P99| 866ms| 877ms | 11ms | 1.270
| UserStore.GetProfilesByUsernames |  Avg| 114ms| 94ms | -20ms | -17.534
| |  P99| 917ms| 887ms | -30ms | -3.270
| UserStore.GetProfilesInChannel |  Avg| 49ms| 153ms | 104ms | 214.420
| |  P99| 238ms| 2.35s | 2.112s | 887.313
| UserStore.GetProfilesNotInChannel |  Avg| 57ms| 38ms | -19ms | -33.430
| |  P99| 244ms| 99ms | -145ms | -59.426
| UserStore.GetUnreadCount |  Avg| 123ms| 108ms | -15ms | -12.243
| |  P99| 980ms| 1.142s | 162ms | 16.537
| UserStore.IsEmpty |  Avg| 58ms| 52ms | -6ms | -10.290
| |  P99| 580ms| 475ms | -105ms | -18.092
| UserStore.Save |  Avg| 78ms| 77ms | -1ms | -1.276
| |  P99| 248ms| 245ms | -3ms | -1.209
| UserStore.Search |  Avg| 413ms| 337ms | -76ms | -18.424
| |  P99| 2.375s| 2.024s | -351ms | -14.780
| UserStore.Update |  Avg| 13ms| 6ms | -7ms | -54.773
| |  P99| 200ms| 49ms | -151ms | -75.313
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 66ms| 57ms | -9ms | -13.580
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 62ms| 50ms | -12ms | -19.483
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.025
| UserTermsOfServiceStore.GetByUser |  Avg| 122ms| 120ms | -2ms | -1.638
| |  P99| 955ms| 955ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 154ms| 136ms | -18ms | -11.682
| |  P99| 1.294s| 1.295s | 1ms | 0.077
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.806s| 1.848s | 42ms | 2.325
| | P99| 9.187s| 9.6s | 413ms | 4.495
| addTeamMember | Avg| 3.63s| 3.392s | -238ms | -6.557
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 617ms| 498ms | -119ms | -19.290
| | P99| 4.019s| 2.477s | -1.542s | -38.370
| autocompleteUsers | Avg| 703ms| 579ms | -124ms | -17.644
| | P99| 3.956s| 2.446s | -1.51s | -38.166
| channelMemberCountsByGroup | Avg| 7ms| 0s | -7ms | -94.762
| | P99| 88ms| 0s | -88ms | -99.999
| createCategoryForTeamForUser | Avg| 246ms| 435ms | 189ms | 76.749
| | P99| 490ms| 990ms | 500ms | 102.037
| createChannel | Avg| 2.03s| 1.16s | -870ms | -42.853
| | P99| 9.55s| 4.775s | -4.775s | -50.000
| createDirectChannel | Avg| 914ms| 777ms | -137ms | -14.987
| | P99| 4.458s| 4.125s | -333ms | -7.469
| createGroupChannel | Avg| 2.399s| 2.074s | -325ms | -13.545
| | P99| 10s| 9.86s | -140ms | -1.400
| createPost | Avg| 4.183s| 2.672s | -1.511s | -36.126
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 315ms| 307ms | -8ms | -2.542
| | P99| 2.148s| 1.987s | -161ms | -7.497
| deleteDraft | Avg| 172ms| 153ms | -19ms | -11.073
| | P99| 1.616s| 1.65s | 34ms | 2.104
| deletePost | Avg| 459ms| 737ms | 278ms | 60.600
| | P99| 991ms| 4.837s | 3.846s | 388.267
| followThreadByUser | Avg| 392ms| 123ms | -269ms | -68.689
| | P99| 4.575s| 488ms | -4.087s | -89.335
| getAllTeams | Avg| 113ms| 111ms | -2ms | -1.765
| | P99| 921ms| 926ms | 5ms | 0.543
| getAnalytics | Avg| 1.318s| 808ms | -510ms | -38.695
| | P99| 2.47s| 995ms | -1.475s | -59.716
| getCategoriesForTeamForUser | Avg| 268ms| 245ms | -23ms | -8.587
| | P99| 2.241s| 2.25s | 9ms | 0.402
| getChannel | Avg| 303ms| 229ms | -74ms | -24.455
| | P99| 2.39s| 2.338s | -52ms | -2.175
| getChannelMember | Avg| 125ms| 124ms | -1ms | -0.802
| | P99| 1.192s| 1.47s | 278ms | 23.324
| getChannelMembers | Avg| 73ms| 86ms | 13ms | 17.919
| | P99| 242ms| 246ms | 4ms | 1.649
| getChannelMembersForTeamForUser | Avg| 140ms| 123ms | -17ms | -12.130
| | P99| 1.106s| 998ms | -108ms | -9.762
| getChannelMembersForUser | Avg| 210ms| 1.588s | 1.378s | 656.915
| | P99| 492ms| 4.9s | 4.408s | 895.027
| getChannelStats | Avg| 142ms| 106ms | -36ms | -25.432
| | P99| 2.234s| 1.878s | -356ms | -15.934
| getChannelUnread | Avg| 144ms| 76ms | -68ms | -47.134
| | P99| 1.522s| 861ms | -661ms | -43.426
| getChannelsForTeamForUser | Avg| 140ms| 126ms | -14ms | -10.035
| | P99| 1.019s| 992ms | -27ms | -2.649
| getChannelsForUser | Avg| 138ms| 101ms | -37ms | -26.835
| | P99| 1.202s| 890ms | -312ms | -25.957
| getClientConfig | Avg| 23ms| 21ms | -2ms | -8.690
| | P99| 405ms| 386ms | -19ms | -4.693
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 178ms| 145ms | -33ms | -18.502
| | P99| 1.894s| 1.046s | -848ms | -44.780
| getFilePreview | Avg| 173ms| 150ms | -23ms | -13.287
| | P99| 1.081s| 994ms | -87ms | -8.051
| getFileThumbnail | Avg| 166ms| 139ms | -27ms | -16.236
| | P99| 1.229s| 1.053s | -176ms | -14.318
| getFilteredUsersStats | Avg| 327ms| 246ms | -81ms | -24.788
| | P99| 498ms| 496ms | -2ms | -0.402
| getGroups | Avg| 272ms| 453ms | 181ms | 66.460
| | P99| 495ms| 985ms | 490ms | 98.990
| getJobsByType | Avg| 176ms| 142ms | -34ms | -19.362
| | P99| 1.985s| 1.735s | -250ms | -12.595
| getPostThread | Avg| 860ms| 722ms | -138ms | -16.047
| | P99| 4.818s| 4.849s | 31ms | 0.643
| getPostsForChannel | Avg| 1.494s| 1.231s | -263ms | -17.603
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 509ms| 471ms | -38ms | -7.462
| | P99| 4.043s| 4.057s | 14ms | 0.346
| getPreferences | Avg| 149ms| 155ms | 6ms | 4.028
| | P99| 1.212s| 1.224s | 12ms | 0.990
| getPrevTrialLicense | Avg| 94ms| 336ms | 242ms | 258.151
| | P99| 493ms| 985ms | 492ms | 99.898
| getProductNotices | Avg| 137ms| 0s | -137ms | -100.309
| | P99| 249ms| 0s | -249ms | -100.201
| getProfileImage | Avg| 91ms| 86ms | -5ms | -5.506
| | P99| 464ms| 472ms | 8ms | 1.724
| getPublicChannelsForTeam | Avg| 197ms| 185ms | -12ms | -6.104
| | P99| 1.915s| 989ms | -926ms | -48.355
| getRolesByNames | Avg| 19ms| 165ms | 146ms | 754.411
| | P99| 241ms| 2.365s | 2.124s | 881.323
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 12ms| 10ms | -2ms | -17.322
| | P99| 244ms| 225ms | -19ms | -7.780
| getTeamMembersForUser | Avg| 92ms| 75ms | -17ms | -18.386
| | P99| 805ms| 738ms | -67ms | -8.328
| getTeamStats | Avg| 546ms| 437ms | -109ms | -19.957
| | P99| 990ms| 985ms | -5ms | -0.505
| getTeamsForUser | Avg| 104ms| 106ms | 2ms | 1.921
| | P99| 876ms| 894ms | 18ms | 2.055
| getTeamsUnreadForUser | Avg| 170ms| 162ms | -8ms | -4.706
| | P99| 1.897s| 1.888s | -9ms | -0.475
| getThreadsForUser | Avg| 170ms| 150ms | -20ms | -11.772
| | P99| 1.736s| 1.729s | -7ms | -0.403
| getUser | Avg| 141ms| 147ms | 6ms | 4.246
| | P99| 1.048s| 1.193s | 145ms | 13.835
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 10ms | 2ms | 23.728
| getUsers | Avg| 48ms| 49ms | 1ms | 2.098
| | P99| 627ms| 686ms | 59ms | 9.413
| getUsersByIds | Avg| 12ms| 10ms | -2ms | -16.579
| | P99| 295ms| 248ms | -47ms | -15.927
| getUsersByNames | Avg| 116ms| 95ms | -21ms | -18.153
| | P99| 926ms| 896ms | -30ms | -3.240
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 104ms| 476ms | 372ms | 359.178
| | P99| 925ms| 2.431s | 1.506s | 162.810
| login | Avg| 382ms| 304ms | -78ms | -20.412
| | P99| 2.461s| 2.387s | -74ms | -3.007
| logout | Avg| 278ms| 205ms | -73ms | -26.221
| | P99| 960ms| 952ms | -8ms | -0.833
| patchPost | Avg| 2.128s| 1.122s | -1.006s | -47.264
| | P99| 10s| 4.836s | -5.164s | -51.640
| removeUserCustomStatus | Avg| 199ms| 195ms | -4ms | -2.006
| | P99| 1.045s| 984ms | -61ms | -5.838
| root | Avg| 0s| 1ms | 1ms | 695.362
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 460ms| 423ms | -37ms | -8.041
| | P99| 2.483s| 3.265s | 782ms | 31.493
| searchAllChannels | Avg| 4.699s| 3.166s | -1.533s | -32.622
| | P99| 10s| 10s | 0s | 0.000
| searchFiles | Avg| 444ms| 0s | -444ms | -99.914
| | P99| 498ms| 0s | -498ms | -100.051
| searchGroupChannels | Avg| 163ms| 149ms | -14ms | -8.593
| | P99| 997ms| 1.524s | 527ms | 52.859
| searchPostsInTeam | Avg| 550ms| 464ms | -86ms | -15.626
| | P99| 4.859s| 6.782s | 1.923s | 39.578
| searchUsers | Avg| 418ms| 340ms | -78ms | -18.656
| | P99| 2.38s| 2.03s | -350ms | -14.703
| setPostReminder | Avg| 759ms| 419ms | -340ms | -44.799
| | P99| 4.425s| 2.41s | -2.015s | -45.536
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 327ms| 297ms | -30ms | -9.166
| | P99| 2.234s| 2.444s | 210ms | 9.401
| updateCategoriesForTeamForUser | Avg| 746ms| 759ms | 13ms | 1.743
| | P99| 4.3s| 3.9s | -400ms | -9.302
| updatePreferences | Avg| 17ms| 16ms | -1ms | -5.837
| | P99| 226ms| 227ms | 1ms | 0.443
| updateReadStateAllThreadsByUser | Avg| 9ms| 2ms | -7ms | -77.084
| | P99| 25ms| 5ms | -20ms | -80.972
| updateReadStateThreadByUser | Avg| 1.257s| 1.07s | -187ms | -14.871
| | P99| 6.79s| 7.543s | 753ms | 11.090
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 410ms| 419ms | 9ms | 2.195
| | P99| 1.287s| 1.123s | -164ms | -12.744
| upsertDraft | Avg| 64ms| 59ms | -5ms | -7.802
| | P99| 892ms| 894ms | 2ms | 0.224
| viewChannel | Avg| 285ms| 246ms | -39ms | -13.663
| | P99| 2.255s| 2.254s | -1ms | -0.044
