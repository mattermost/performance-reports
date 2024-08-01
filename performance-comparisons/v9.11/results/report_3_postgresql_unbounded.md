### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.GetDraftsForUser | avg | 1ms | 28ms | 27ms | 1849.17
| ProductNoticesStore.GetViews | avg | 2ms | 28ms | 26ms | 1400.83
| ChannelStore.GetMembers | avg | 4ms | 38ms | 34ms | 762.75
| PostStore.GetPostReminders | avg | 10ms | 59ms | 49ms | 486.72
| PostStore.SetPostReminder | avg | 16ms | 81ms | 65ms | 405.32
| ChannelStore.GetMembersForUserWithPagination | avg | 10ms | 38ms | 28ms | 282.18
| BotStore.Get | avg | 6ms | 21ms | 15ms | 249.49
| PluginStore.Get | avg | 4ms | 13ms | 9ms | 216.72
| RoleStore.ChannelHigherScopedPermissions | avg | 6ms | 18ms | 12ms | 211.28
| DraftStore.Get | avg | 7ms | 22ms | 15ms | 201.58
| PostStore.GetPostReminderMetadata | avg | 7ms | 18ms | 11ms | 161.26
| SessionStore.GetSessionsExpired | avg | 7ms | 18ms | 11ms | 154.62
| UserStore.GetProfilesNotInChannel | avg | 9ms | 21ms | 12ms | 135.88
| ThreadStore.MarkAllAsReadByTeam | avg | 10ms | 23ms | 13ms | 125.93
| StatusStore.UpdateExpiredDNDStatuses | avg | 9ms | 19ms | 10ms | 107.70
| JobStore.UpdateStatus | avg | 6ms | 12ms | 6ms | 93.84
| TokenStore.Cleanup | avg | 15ms | 29ms | 14ms | 93.39
| JobStore.GetAllByTypePage | avg | 10ms | 19ms | 9ms | 88.30
| UserStore.GetByUsername | avg | 9ms | 16ms | 7ms | 78.08
| ChannelStore.GetChannelUnread | avg | 9ms | 14ms | 5ms | 54.26
| StatusStore.SaveOrUpdate | avg | 15ms | 23ms | 8ms | 52.64
| LinkMetadataStore.Save | avg | 10ms | 15ms | 5ms | 51.71
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 6ms | 2ms | 51.64
| PostAcknowledgementStore.GetForPost | avg | 6ms | 9ms | 3ms | 47.82
| PostStore.Delete | avg | 46ms | 68ms | 22ms | 47.65
| TeamStore.Get | avg | 7ms | 10ms | 3ms | 40.69
| UserStore.GetUnreadCount | avg | 8ms | 11ms | 3ms | 37.94
| GroupStore.GetByName | avg | 5ms | 7ms | 2ms | 37.61
| LinkMetadataStore.Get | avg | 8ms | 11ms | 3ms | 36.32
| PostPriorityStore.GetForPosts | avg | 11ms | 15ms | 4ms | 35.16
| ChannelStore.GetPinnedPostCount | avg | 9ms | 12ms | 3ms | 33.21
| TeamStore.GetAllPage | avg | 6ms | 8ms | 2ms | 32.16
| ChannelStore.GetFileCount | avg | 10ms | 13ms | 3ms | 29.32
| UserStore.GetProfilesByUsernames | avg | 10ms | 13ms | 3ms | 29.31
| PostStore.GetEtag | avg | 10ms | 13ms | 3ms | 29.28
| ComplianceStore.MessageExport | avg | 14ms | 18ms | 4ms | 28.94
| ChannelStore.GetMember | avg | 10ms | 13ms | 3ms | 28.87
| JobStore.UpdateStatusOptimistically | avg | 7ms | 9ms | 2ms | 28.84
| ThreadStore.GetTotalThreads | avg | 7ms | 9ms | 2ms | 28.81
| ThreadStore.GetTotalUnreadThreads | avg | 7ms | 9ms | 2ms | 28.61
| TeamStore.GetChannelUnreadsForAllTeams | avg | 7ms | 9ms | 2ms | 27.68
| PostPriorityStore.GetForPost | avg | 7ms | 9ms | 2ms | 27.67
| PostAcknowledgementStore.GetForPosts | avg | 11ms | 14ms | 3ms | 27.49
| ThreadStore.GetTotalUnreadMentions | avg | 7ms | 9ms | 2ms | 27.20
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 7ms | 9ms | 2ms | 26.93
| PreferenceStore.GetAll | avg | 7ms | 9ms | 2ms | 26.81
| ChannelStore.Get | avg | 11ms | 14ms | 3ms | 26.65
| ReactionStore.GetForPost | avg | 8ms | 10ms | 2ms | 26.40
| ThreadStore.GetMembershipForUser | avg | 8ms | 10ms | 2ms | 24.96
| PostStore.GetSingle | avg | 8ms | 10ms | 2ms | 24.76
| ThreadStore.GetThreadForUser | avg | 16ms | 20ms | 4ms | 24.36
| ChannelStore.UpdateSidebarChannelsByPreferences | avg | 8ms | 10ms | 2ms | 24.25
| ThreadStore.GetThreadFollowers | avg | 8ms | 10ms | 2ms | 24.24
| ThreadStore.GetThreadsForUser | avg | 12ms | 15ms | 3ms | 24.20
| FileInfoStore.SetContent | avg | 21ms | 26ms | 5ms | 24.17
| PostStore.GetPostIdBeforeTime | avg | 8ms | 10ms | 2ms | 24.11
| ChannelStore.CreateSidebarCategory | avg | 122ms | 151ms | 29ms | 23.76
| EmojiStore.GetByName | avg | 8ms | 10ms | 2ms | 23.64
| ChannelStore.SearchGroupChannels | avg | 13ms | 16ms | 3ms | 23.44
| PluginStore.List | avg | 9ms | 11ms | 2ms | 23.27
| ThreadStore.UpdateMembership | avg | 9ms | 11ms | 2ms | 22.96
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 9ms | 11ms | 2ms | 22.79
| PostStore.GetPostsByThread | avg | 13ms | 16ms | 3ms | 22.40
| ThreadStore.MarkAsRead | avg | 9ms | 11ms | 2ms | 22.17
| GroupStore.GetGroups | avg | 9ms | 11ms | 2ms | 21.98
| PostStore.GetPostsAfter | avg | 9ms | 11ms | 2ms | 21.96
| StatusStore.UpdateLastActivityAt | avg | 9ms | 11ms | 2ms | 21.93
| FileInfoStore.Get | avg | 10ms | 12ms | 2ms | 21.01
| ThreadStore.MaintainMembership | avg | 19ms | 23ms | 4ms | 20.82
| FileInfoStore.GetForPost | avg | 10ms | 12ms | 2ms | 20.57
| SessionStore.UpdateLastActivityAt | avg | 10ms | 12ms | 2ms | 20.47
| PreferenceStore.Get | avg | 10ms | 12ms | 2ms | 20.21
| ChannelStore.GetChannelsByUser | avg | 10ms | 12ms | 2ms | 20.19
| ChannelStore.CreateDirectChannel | avg | 70ms | 84ms | 14ms | 20.10
| ChannelStore.GetChannels | avg | 10ms | 12ms | 2ms | 19.87
| ChannelStore.CreateInitialSidebarCategories | avg | 40ms | 48ms | 8ms | 19.86
| ThreadStore.GetThreadUnreadReplyCount | avg | 15ms | 18ms | 3ms | 19.61
| ChannelStore.UpdateLastViewedAt | avg | 10ms | 12ms | 2ms | 19.50
| ChannelStore.GetAllChannelMembersForUser | avg | 10ms | 12ms | 2ms | 19.43
| ThreadStore.GetTeamsUnreadForUser | avg | 10ms | 12ms | 2ms | 19.26
| PostStore.Get | avg | 21ms | 25ms | 4ms | 19.20
| UserStore.GetProfileByIds | avg | 11ms | 13ms | 2ms | 18.78
| JobStore.GetAllByStatus | avg | 11ms | 13ms | 2ms | 18.76
| ChannelStore.GetMembersForUser | avg | 11ms | 13ms | 2ms | 18.24
| StatusStore.GetByIds | avg | 12ms | 14ms | 2ms | 17.25
| PostStore.GetPostsBefore | avg | 12ms | 14ms | 2ms | 16.76
| WebhookStore.GetOutgoingByTeam | avg | 12ms | 14ms | 2ms | 16.47
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 24ms | 28ms | 4ms | 16.44
| SessionStore.Save | avg | 12ms | 14ms | 2ms | 16.38
| PostStore.GetPostsSince | avg | 24ms | 28ms | 4ms | 16.34
| PostStore.AnalyticsPostCount | avg | 488ms | 566ms | 78ms | 16.00
| ProductNoticesStore.View | avg | 63ms | 73ms | 10ms | 15.85
| FileInfoStore.Save | avg | 13ms | 15ms | 2ms | 15.60
| PostStore.Save | avg | 33ms | 38ms | 5ms | 15.31
| ChannelStore.GetMemberForPost | avg | 15ms | 17ms | 2ms | 13.23
| SessionStore.Get | avg | 15ms | 17ms | 2ms | 13.16
| PreferenceStore.Save | avg | 23ms | 26ms | 3ms | 12.93
| ChannelStore.SaveMember | avg | 55ms | 62ms | 7ms | 12.79
| LicenseStore.GetAll | avg | 16ms | 18ms | 2ms | 12.27
| ProductNoticesStore.ClearOldNotices | avg | 25ms | 28ms | 3ms | 11.91
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 28ms | 31ms | 3ms | 10.72
| UserStore.GetProfilesInChannel | avg | 161ms | 178ms | 17ms | 10.56
| ChannelStore.AutocompleteInTeamForSearch | avg | 124ms | 136ms | 12ms | 9.70
| TeamStore.SaveMember | avg | 42ms | 46ms | 4ms | 9.54
| UserStore.Update | avg | 22ms | 24ms | 2ms | 8.98
| UserStore.AutocompleteUsersInChannel | avg | 71ms | 77ms | 6ms | 8.44
| UserStore.Search | avg | 52ms | 56ms | 4ms | 7.67
| ChannelStore.GetPublicChannelsForTeam | avg | 30ms | 32ms | 2ms | 6.74
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 30ms | 32ms | 2ms | 6.60
| UserStore.GetAllProfilesInChannel | avg | 439ms | 467ms | 28ms | 6.38
| ChannelStore.GetMemberCount | avg | 32ms | 34ms | 2ms | 6.23
| ChannelStore.Autocomplete | avg | 58ms | 61ms | 3ms | 5.18
| TeamStore.GetActiveMemberCount | avg | 66ms | 69ms | 3ms | 4.52
| UserStore.Save | avg | 88ms | 91ms | 3ms | 3.43
| ChannelStore.UpdateSidebarCategories | avg | 150ms | 155ms | 5ms | 3.33
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.GetDraftsForUser | p99 | 5ms | 99ms | 94ms | 1898.99
| ProductNoticesStore.GetViews | p99 | 5ms | 50ms | 45ms | 908.42
| ChannelStore.GetMembers | p99 | 10ms | 99ms | 89ms | 898.67
| SessionStore.GetSessionsExpired | p99 | 25ms | 237ms | 212ms | 860.91
| BotStore.Get | p99 | 43ms | 231ms | 188ms | 432.18
| ChannelStore.GetMembersForUserWithPagination | p99 | 47ms | 237ms | 190ms | 403.62
| PostStore.GetPostReminders | p99 | 87ms | 437ms | 350ms | 402.30
| RoleStore.ChannelHigherScopedPermissions | p99 | 43ms | 213ms | 170ms | 393.84
| JobStore.UpdateStatus | p99 | 41ms | 199ms | 158ms | 383.03
| UserStore.GetProfilesNotInChannel | p99 | 48ms | 226ms | 178ms | 370.83
| LinkMetadataStore.Save | p99 | 70ms | 327ms | 257ms | 367.13
| PluginStore.Get | p99 | 24ms | 95ms | 71ms | 294.61
| PostStore.GetPostReminderMetadata | p99 | 46ms | 174ms | 128ms | 280.55
| JobStore.GetAllByTypePage | p99 | 90ms | 236ms | 146ms | 161.78
| StatusStore.UpdateExpiredDNDStatuses | p99 | 87ms | 212ms | 125ms | 143.68
| TeamStore.GetActiveMemberCount | p99 | 99ms | 238ms | 139ms | 139.73
| ChannelStore.UpdateSidebarCategories | p99 | 932ms | 2.185s | 1.253s | 134.49
| JobStore.UpdateStatusOptimistically | p99 | 64ms | 147ms | 83ms | 130.71
| UserStore.GetByUsername | p99 | 88ms | 192ms | 104ms | 118.10
| PostStore.SetPostReminder | p99 | 225ms | 478ms | 253ms | 112.69
| UserStore.Count | p99 | 98ms | 207ms | 109ms | 111.10
| PostPersistentNotificationStore.DeleteExpired | p99 | 24ms | 48ms | 24ms | 101.22
| ThreadStore.MarkAllAsReadByTeam | p99 | 49ms | 98ms | 49ms | 100.00
| TokenStore.Cleanup | p99 | 49ms | 98ms | 49ms | 100.00
| PostStore.Delete | p99 | 445ms | 855ms | 410ms | 92.13
| FileInfoStore.Save | p99 | 98ms | 183ms | 85ms | 86.70
| FileInfoStore.GetForPost | p99 | 98ms | 167ms | 69ms | 70.06
| JobStore.GetCountByStatusAndType | p99 | 90ms | 145ms | 55ms | 61.45
| ChannelStore.GetMembersForUser | p99 | 100ms | 159ms | 59ms | 59.15
| UserStore.GetProfilesByUsernames | p99 | 100ms | 158ms | 58ms | 58.01
| PostStore.GetEtag | p99 | 108ms | 166ms | 58ms | 53.50
| ChannelStore.GetMember | p99 | 97ms | 148ms | 51ms | 52.63
| PreferenceStore.Get | p99 | 100ms | 152ms | 52ms | 52.16
| FileInfoStore.Get | p99 | 99ms | 150ms | 51ms | 51.35
| ChannelStore.GetChannels | p99 | 104ms | 156ms | 52ms | 49.97
| ChannelStore.GetChannelUnread | p99 | 94ms | 139ms | 45ms | 48.04
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.485s | 3.658s | 1.173s | 47.20
| UserStore.GetProfileByIds | p99 | 113ms | 165ms | 52ms | 46.16
| JobStore.GetAllByStatus | p99 | 123ms | 176ms | 53ms | 43.15
| ThreadStore.GetThreadsForUser | p99 | 121ms | 173ms | 52ms | 43.13
| PostStore.GetPostsBefore | p99 | 118ms | 169ms | 51ms | 43.12
| ChannelStore.GetFileCount | p99 | 96ms | 137ms | 41ms | 42.90
| UserStore.GetUnreadCount | p99 | 89ms | 125ms | 36ms | 40.37
| ChannelStore.SearchGroupChannels | p99 | 127ms | 178ms | 51ms | 40.03
| ChannelStore.GetSidebarCategory | p99 | 310ms | 430ms | 120ms | 38.71
| StatusStore.GetByIds | p99 | 145ms | 201ms | 56ms | 38.58
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 96ms | 133ms | 37ms | 38.47
| ChannelStore.Get | p99 | 134ms | 185ms | 51ms | 38.11
| LinkMetadataStore.Get | p99 | 95ms | 130ms | 35ms | 36.92
| ChannelStore.GetPinnedPostCount | p99 | 98ms | 134ms | 36ms | 36.76
| ThreadStore.GetMembershipForUser | p99 | 94ms | 128ms | 34ms | 36.35
| ProductNoticesStore.View | p99 | 576ms | 783ms | 207ms | 35.91
| UserStore.GetAllProfiles | p99 | 56ms | 76ms | 20ms | 35.61
| ThreadStore.GetThreadUnreadReplyCount | p99 | 100ms | 135ms | 35ms | 35.08
| ChannelStore.GetChannelsByUser | p99 | 99ms | 133ms | 34ms | 34.40
| TeamStore.GetMember | p99 | 42ms | 56ms | 14ms | 33.65
| PostStore.GetSingle | p99 | 93ms | 124ms | 31ms | 33.26
| SessionStore.Save | p99 | 129ms | 170ms | 41ms | 31.68
| PluginStore.Delete | p99 | 60ms | 79ms | 19ms | 31.65
| ComplianceStore.MessageExport | p99 | 174ms | 228ms | 54ms | 31.12
| PluginStore.SetWithOptions | p99 | 114ms | 149ms | 35ms | 30.73
| WebhookStore.GetOutgoingByTeam | p99 | 139ms | 181ms | 42ms | 30.30
| UserStore.UpdateLastLogin | p99 | 65ms | 84ms | 19ms | 29.41
| ChannelStore.GetMemberForPost | p99 | 142ms | 181ms | 39ms | 27.40
| ThreadStore.MarkAllAsReadByChannels | p99 | 96ms | 122ms | 26ms | 27.14
| PostAcknowledgementStore.GetForPost | p99 | 75ms | 95ms | 20ms | 26.59
| GroupStore.GetGroups | p99 | 94ms | 119ms | 25ms | 26.52
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 72ms | 89ms | 17ms | 23.56
| ThreadStore.GetTeamsUnreadForUser | p99 | 141ms | 173ms | 32ms | 22.73
| TeamStore.Get | p99 | 91ms | 110ms | 19ms | 20.88
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 240ms | 289ms | 49ms | 20.45
| PostAcknowledgementStore.GetForPosts | p99 | 177ms | 213ms | 36ms | 20.37
| PostStore.GetPostsByThread | p99 | 95ms | 114ms | 19ms | 20.01
| TeamStore.SaveMember | p99 | 245ms | 293ms | 48ms | 19.59
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 66ms | 79ms | 13ms | 19.55
| PostPriorityStore.GetForPosts | p99 | 179ms | 213ms | 34ms | 19.04
| PostStore.GetPostIdAfterTime | p99 | 69ms | 82ms | 13ms | 18.98
| PostStore.Save | p99 | 343ms | 407ms | 64ms | 18.65
| ReactionStore.GetForPost | p99 | 85ms | 100ms | 15ms | 17.66
| StatusStore.SaveOrUpdate | p99 | 211ms | 248ms | 37ms | 17.50
| FileInfoStore.SetContent | p99 | 196ms | 230ms | 34ms | 17.35
| PostStore.GetPostsAfter | p99 | 92ms | 108ms | 16ms | 17.33
| ThreadStore.GetThreadFollowers | p99 | 93ms | 109ms | 16ms | 17.12
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 92ms | 106ms | 14ms | 15.25
| ThreadStore.GetTotalUnreadMentions | p99 | 87ms | 100ms | 13ms | 15.01
| UserStore.Save | p99 | 365ms | 419ms | 54ms | 14.79
| ThreadStore.MarkAsRead | p99 | 84ms | 96ms | 12ms | 14.28
| ClusterDiscoveryStore.SetLastPingAt | p99 | 163ms | 186ms | 23ms | 14.11
| SystemStore.GetByName | p99 | 78ms | 89ms | 11ms | 14.04
| PostStore.GetPosts | p99 | 79ms | 90ms | 11ms | 14.01
| ThreadStore.GetTotalThreads | p99 | 86ms | 98ms | 12ms | 13.91
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 87ms | 99ms | 12ms | 13.83
| ThreadStore.GetTotalUnreadThreads | p99 | 87ms | 99ms | 12ms | 13.83
| UserStore.UpdateFailedPasswordAttempts | p99 | 81ms | 92ms | 11ms | 13.52
| UserStore.Get | p99 | 82ms | 93ms | 11ms | 13.42
| SessionStore.GetLRUSessions | p99 | 76ms | 86ms | 10ms | 13.18
| TeamStore.GetAllPage | p99 | 86ms | 97ms | 11ms | 12.79
| UserStore.GetForLogin | p99 | 83ms | 93ms | 10ms | 12.02
| ChannelStore.GetMemberCount | p99 | 183ms | 205ms | 22ms | 11.99
| PostPriorityStore.GetForPost | p99 | 120ms | 134ms | 14ms | 11.64
| PostPersistentNotificationStore.GetSingle | p99 | 86ms | 96ms | 10ms | 11.59
| UserStore.AutocompleteUsersInChannel | p99 | 359ms | 399ms | 40ms | 11.13
| ThreadStore.GetThreadForUser | p99 | 199ms | 221ms | 22ms | 11.04
| StatusStore.Get | p99 | 79ms | 87ms | 8ms | 10.17
| TeamStore.GetTeamsByUserId | p99 | 89ms | 98ms | 9ms | 10.16
| GroupStore.GetByName | p99 | 80ms | 88ms | 8ms | 9.99
| UserTermsOfServiceStore.GetByUser | p99 | 81ms | 89ms | 8ms | 9.88
| ChannelStore.GetMemberLastViewedAt | p99 | 81ms | 89ms | 8ms | 9.83
| UserStore.IsEmpty | p99 | 41ms | 45ms | 4ms | 9.76
| UserStore.UpdateUpdateAt | p99 | 72ms | 79ms | 7ms | 9.75
| AuditStore.Save | p99 | 82ms | 90ms | 8ms | 9.70
| ChannelStore.CreateInitialSidebarCategories | p99 | 441ms | 483ms | 42ms | 9.53
| ChannelStore.CreateDirectChannel | p99 | 709ms | 775ms | 66ms | 9.31
| ThreadStore.UpdateMembership | p99 | 87ms | 95ms | 8ms | 9.16
| ChannelStore.IncrementMentionCount | p99 | 89ms | 97ms | 8ms | 8.95
| ChannelStore.GetGuestCount | p99 | 91ms | 99ms | 8ms | 8.79
| PostStore.GetPostsSince | p99 | 203ms | 220ms | 17ms | 8.38
| PluginStore.List | p99 | 87ms | 94ms | 7ms | 8.09
| ChannelStore.GetAllChannelMembersForUser | p99 | 90ms | 97ms | 7ms | 7.77
| SessionStore.UpdateLastActivityAt | p99 | 91ms | 98ms | 7ms | 7.71
| ChannelStore.SaveMember | p99 | 460ms | 495ms | 35ms | 7.61
| PostStore.GetPostIdBeforeTime | p99 | 92ms | 99ms | 7ms | 7.59
| SessionStore.Get | p99 | 199ms | 214ms | 15ms | 7.54
| ChannelStore.UpdateLastViewedAt | p99 | 93ms | 100ms | 7ms | 7.52
| EmojiStore.GetByName | p99 | 96ms | 103ms | 7ms | 7.26
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 222ms | 238ms | 16ms | 7.19
| JobStore.GetNewestJobByStatusesAndType | p99 | 84ms | 90ms | 6ms | 7.12
| PostPersistentNotificationStore.Get | p99 | 44ms | 47ms | 3ms | 6.84
| ChannelStore.GetByName | p99 | 89ms | 95ms | 6ms | 6.71
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 90ms | 96ms | 6ms | 6.68
| UserStore.Update | p99 | 210ms | 224ms | 14ms | 6.66
| StatusStore.UpdateLastActivityAt | p99 | 92ms | 98ms | 6ms | 6.55
| PreferenceStore.GetAll | p99 | 92ms | 98ms | 6ms | 6.49
| JobStore.Get | p99 | 175ms | 186ms | 11ms | 6.29
| PostStore.Get | p99 | 224ms | 238ms | 14ms | 6.24
| ThreadStore.MaintainMembership | p99 | 224ms | 236ms | 12ms | 5.36
| TeamStore.GetTeamsForUser | p99 | 90ms | 94ms | 4ms | 4.46
| UserStore.GetAllProfilesInChannel | p99 | 2.247s | 2.334s | 87ms | 3.87
| UserStore.Search | p99 | 232ms | 240ms | 8ms | 3.44
| FileInfoStore.AttachToPost | p99 | 207ms | 214ms | 7ms | 3.38
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 93ms | 96ms | 3ms | 3.23
| PreferenceStore.Save | p99 | 241ms | 248ms | 7ms | 2.91
| ThreadStore.Get | p99 | 91ms | 93ms | 2ms | 2.21
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 4ms | 0s | -4ms | -108.20
| ChannelStore.GetMemberCountsByGroup | avg | 14ms | 0s | -14ms | -98.85
| RetentionPolicyStore.GetCount | avg | 2ms | 0s | -2ms | -98.48
| TeamStore.GetMany | avg | 6ms | 0s | -6ms | -97.11
| ChannelStore.GetChannelsByIds | avg | 9ms | 0s | -9ms | -96.04
| PostStore.GetPostsByIds | avg | 10ms | 0s | -10ms | -95.67
| PostPersistentNotificationStore.UpdateLastActivity | avg | 6ms | 0s | -6ms | -94.54
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 30ms | 7ms | -23ms | -75.71
| ChannelStore.AnalyticsTypeCount | avg | 29ms | 14ms | -15ms | -51.05
| UserStore.GetMany | avg | 14ms | 7ms | -7ms | -49.28
| UserStore.AnalyticsGetInactiveUsersCount | avg | 8ms | 5ms | -3ms | -39.06
| PreferenceStore.DeleteCategoryAndName | avg | 28ms | 17ms | -11ms | -38.96
| JobStore.GetCountByStatusAndType | avg | 11ms | 8ms | -3ms | -27.52
| JobStore.GetNewestJobByStatusesAndType | avg | 8ms | 6ms | -2ms | -25.28
| CommandWebhookStore.Cleanup | avg | 16ms | 12ms | -4ms | -24.30
| ChannelStore.GetTeamChannels | avg | 40ms | 31ms | -9ms | -22.24
| UserStore.AnalyticsActiveCount | avg | 59ms | 47ms | -12ms | -20.44
| UserStore.Count | avg | 31ms | 25ms | -6ms | -19.28
| JobStore.UpdateOptimistically | avg | 12ms | 10ms | -2ms | -16.94
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 20ms | 18ms | -2ms | -10.01
| PostStore.SearchPostsForUser | avg | 256ms | 231ms | -25ms | -9.75
| TeamStore.GetTotalMemberCount | avg | 68ms | 62ms | -6ms | -8.87
| ChannelStore.Save | avg | 46ms | 42ms | -4ms | -8.71
| ChannelStore.GetSidebarCategory | avg | 35ms | 32ms | -3ms | -8.50
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 49ms | 0s | -49ms | -100.50
| TeamStore.GetMany | p99 | 24ms | 0s | -24ms | -100.21
| ChannelStore.GetMemberCountsByGroup | p99 | 91ms | 0s | -91ms | -99.94
| ChannelStore.GetChannelsByIds | p99 | 48ms | 0s | -48ms | -99.48
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 24ms | 0s | -24ms | -98.96
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 99ms | 25ms | -74ms | -74.75
| ChannelStore.AnalyticsTypeCount | p99 | 98ms | 25ms | -73ms | -74.46
| UserStore.AnalyticsActiveCount | p99 | 244ms | 99ms | -145ms | -59.43
| JobStore.Save | p99 | 145ms | 66ms | -79ms | -54.48
| PreferenceStore.DeleteCategoryAndName | p99 | 445ms | 207ms | -238ms | -53.48
| LicenseStore.GetAll | p99 | 98ms | 49ms | -49ms | -50.26
| EmojiStore.GetMultipleByName | p99 | 48ms | 24ms | -24ms | -49.48
| CommandWebhookStore.Cleanup | p99 | 49ms | 25ms | -24ms | -48.98
| PostStore.Update | p99 | 385ms | 271ms | -114ms | -29.61
| UserAccessTokenStore.GetByToken | p99 | 82ms | 61ms | -21ms | -25.61
| ChannelStore.Save | p99 | 441ms | 355ms | -86ms | -19.49
| UserStore.GetMany | p99 | 94ms | 83ms | -11ms | -11.64
| TeamStore.GetTotalMemberCount | p99 | 238ms | 226ms | -12ms | -5.04
| ChannelStore.GetTeamChannels | p99 | 238ms | 226ms | -12ms | -5.04
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 217ms | 207ms | -10ms | -4.61
| JobStore.UpdateOptimistically | p99 | 97ms | 95ms | -2ms | -2.06
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 6ms | 63ms | 57ms | 1022.76
| upsertDraft | avg | 2ms | 17ms | 15ms | 871.94
| patchPost | avg | 105ms | 1.015s | 910ms | 867.91
| getChannelMembersForUser | avg | 8ms | 38ms | 30ms | 372.99
| setPostReminder | avg | 53ms | 200ms | 147ms | 278.77
| deleteDraft | avg | 5ms | 13ms | 8ms | 151.26
| updateReadStateAllThreadsByUser | avg | 10ms | 23ms | 13ms | 124.92
| getGroups | avg | 8ms | 15ms | 7ms | 84.59
| getJobsByType | avg | 11ms | 19ms | 8ms | 75.37
| getFilteredUsersStats | avg | 30ms | 50ms | 20ms | 67.59
| getAnalytics | avg | 77ms | 128ms | 51ms | 66.26
| getChannelUnread | avg | 11ms | 16ms | 5ms | 45.73
| deletePost | avg | 77ms | 112ms | 35ms | 45.68
| getChannel | avg | 29ms | 38ms | 9ms | 31.42
| searchGroupChannels | avg | 13ms | 17ms | 4ms | 30.08
| getTeamMember | avg | 10ms | 13ms | 3ms | 29.45
| getChannelsForUser | avg | 10ms | 13ms | 3ms | 29.04
| getPostThread | avg | 50ms | 64ms | 14ms | 28.19
| getChannelsForTeamForUser | avg | 11ms | 14ms | 3ms | 26.28
| viewChannel | avg | 39ms | 49ms | 10ms | 25.32
| getAllTeams | avg | 8ms | 10ms | 2ms | 24.83
| getPreferences | avg | 8ms | 10ms | 2ms | 24.75
| getThreadsForUser | avg | 13ms | 16ms | 3ms | 23.07
| getPostsForChannel | avg | 93ms | 114ms | 21ms | 22.65
| getUser | avg | 13ms | 16ms | 3ms | 22.62
| createCategoryForTeamForUser | avg | 129ms | 157ms | 28ms | 21.70
| getTeamMembersForUser | avg | 9ms | 11ms | 2ms | 21.52
| unfollowThreadByUser | avg | 47ms | 57ms | 10ms | 21.23
| getTeamsUnreadForUser | avg | 14ms | 17ms | 3ms | 21.10
| updatePreferences | avg | 38ms | 46ms | 8ms | 20.85
| updateReadStateThreadByUser | avg | 125ms | 150ms | 25ms | 20.03
| getUsersByNames | avg | 11ms | 13ms | 2ms | 18.40
| getChannelMember | avg | 23ms | 27ms | 4ms | 17.24
| getPostsForChannelAroundLastUnread | avg | 41ms | 48ms | 7ms | 16.97
| getChannelMembersForTeamForUser | avg | 12ms | 14ms | 2ms | 16.87
| getCategoriesForTeamForUser | avg | 25ms | 29ms | 4ms | 15.92
| getClientConfig | avg | 19ms | 22ms | 3ms | 15.79
| createPost | avg | 804ms | 928ms | 124ms | 15.43
| getTeamStats | avg | 85ms | 98ms | 13ms | 15.37
| saveReaction | avg | 34ms | 39ms | 5ms | 14.68
| getUsers | avg | 14ms | 16ms | 2ms | 14.44
| addChannelMember | avg | 616ms | 697ms | 81ms | 13.15
| autocompleteChannelsForTeamForSearch | avg | 124ms | 137ms | 13ms | 10.50
| createDirectChannel | avg | 752ms | 827ms | 75ms | 9.97
| createUser | avg | 322ms | 354ms | 32ms | 9.94
| getPrevTrialLicense | avg | 21ms | 23ms | 2ms | 9.65
| getFileThumbnail | avg | 52ms | 57ms | 5ms | 9.59
| autocompleteUsers | avg | 63ms | 69ms | 6ms | 9.58
| getPublicChannelsForTeam | avg | 31ms | 34ms | 3ms | 9.53
| addTeamMember | avg | 1.364s | 1.484s | 120ms | 8.80
| getFilePreview | avg | 64ms | 69ms | 5ms | 7.78
| removeUserCustomStatus | avg | 436ms | 469ms | 33ms | 7.56
| searchUsers | avg | 55ms | 59ms | 4ms | 7.30
| login | avg | 216ms | 230ms | 14ms | 6.49
| searchAllChannels | avg | 59ms | 62ms | 3ms | 5.10
| uploadFileStream | avg | 486ms | 510ms | 24ms | 4.93
| createGroupChannel | avg | 1.183s | 1.241s | 58ms | 4.90
| logout | avg | 171ms | 173ms | 2ms | 1.17
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 10ms | 246ms | 236ms | 2382.99
| getChannelMembersForUser | p99 | 10ms | 238ms | 228ms | 2290.58
| upsertDraft | p99 | 5ms | 98ms | 93ms | 1877.29
| patchPost | p99 | 885ms | 10s | 9.115s | 1029.96
| setPostReminder | p99 | 242ms | 2.11s | 1.868s | 773.50
| deletePost | p99 | 445ms | 2.065s | 1.62s | 364.03
| getJobsByType | p99 | 90ms | 236ms | 146ms | 161.78
| getFilteredUsersStats | p99 | 98ms | 246ms | 148ms | 151.02
| getGroupsAssociatedToChannelsByTeam | p99 | 10ms | 25ms | 15ms | 150.70
| updateCategoriesForTeamForUser | p99 | 967ms | 2.29s | 1.323s | 136.86
| updateReadStateAllThreadsByUser | p99 | 49ms | 98ms | 49ms | 100.00
| getGroups | p99 | 25ms | 49ms | 24ms | 97.08
| getTeamStats | p99 | 242ms | 460ms | 218ms | 90.01
| followThreadByUser | p99 | 244ms | 433ms | 189ms | 77.34
| getTeamMember | p99 | 97ms | 168ms | 71ms | 73.56
| addChannelMember | p99 | 2.497s | 4.284s | 1.787s | 71.56
| getAllTeams | p99 | 103ms | 159ms | 56ms | 54.35
| getPostsForChannel | p99 | 995ms | 1.533s | 538ms | 54.06
| createGroupChannel | p99 | 4.842s | 7.4s | 2.558s | 52.83
| getChannelUnread | p99 | 115ms | 174ms | 59ms | 51.47
| autocompleteChannelsForTeamForSearch | p99 | 2.485s | 3.658s | 1.173s | 47.20
| getUsersByNames | p99 | 124ms | 174ms | 50ms | 40.27
| getUserStatusesByIds | p99 | 40ms | 56ms | 16ms | 40.04
| getChannelMembersForTeamForUser | p99 | 130ms | 182ms | 52ms | 39.93
| createDirectChannel | p99 | 3.216s | 4.466s | 1.25s | 38.87
| getFileThumbnail | p99 | 250ms | 344ms | 94ms | 37.68
| searchGroupChannels | p99 | 144ms | 194ms | 50ms | 34.80
| getChannelStats | p99 | 97ms | 128ms | 31ms | 31.98
| getPreferences | p99 | 97ms | 127ms | 30ms | 30.82
| saveReaction | p99 | 291ms | 373ms | 82ms | 28.14
| getChannel | p99 | 249ms | 314ms | 65ms | 26.12
| getThreadsForUser | p99 | 154ms | 193ms | 39ms | 25.27
| getChannelsForTeamForUser | p99 | 148ms | 184ms | 36ms | 24.29
| getChannelsForUser | p99 | 125ms | 152ms | 27ms | 21.56
| getFilePreview | p99 | 324ms | 392ms | 68ms | 20.99
| getUsersByIds | p99 | 43ms | 52ms | 9ms | 20.71
| getTeamMembersForUser | p99 | 145ms | 173ms | 28ms | 19.35
| autocompleteUsers | p99 | 318ms | 378ms | 60ms | 18.88
| getChannelMember | p99 | 237ms | 273ms | 36ms | 15.20
| addTeamMember | p99 | 7.702s | 8.856s | 1.154s | 14.98
| removeUserCustomStatus | p99 | 2.029s | 2.306s | 277ms | 13.65
| getTeamsForUser | p99 | 93ms | 103ms | 10ms | 10.73
| viewChannel | p99 | 424ms | 467ms | 43ms | 10.15
| getPostThread | p99 | 457ms | 495ms | 38ms | 8.32
| updateReadStateThreadByUser | p99 | 892ms | 963ms | 71ms | 7.96
| createUser | p99 | 2.182s | 2.349s | 167ms | 7.65
| getPostsForChannelAroundLastUnread | p99 | 462ms | 497ms | 35ms | 7.58
| getUser | p99 | 226ms | 243ms | 17ms | 7.52
| getTeamsUnreadForUser | p99 | 206ms | 220ms | 14ms | 6.81
| login | p99 | 2.082s | 2.221s | 139ms | 6.68
| updatePreferences | p99 | 380ms | 405ms | 25ms | 6.57
| getUsers | p99 | 222ms | 236ms | 14ms | 6.31
| getCategoriesForTeamForUser | p99 | 227ms | 241ms | 14ms | 6.17
| getClientConfig | p99 | 232ms | 246ms | 14ms | 6.03
| unfollowThreadByUser | p99 | 411ms | 435ms | 24ms | 5.84
| createPost | p99 | 4.608s | 4.861s | 253ms | 5.49
| uploadFileStream | p99 | 2.205s | 2.314s | 109ms | 4.94
| searchUsers | p99 | 236ms | 243ms | 7ms | 2.97
| getPublicChannelsForTeam | p99 | 203ms | 209ms | 6ms | 2.95
| getProfileImage | p99 | 471ms | 476ms | 5ms | 1.06
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 15ms | 0s | -15ms | -100.61
| getRolesByNames | avg | 20ms | 2ms | -18ms | -89.63
| followThreadByUser | avg | 60ms | 51ms | -9ms | -14.90
| createChannel | avg | 804ms | 729ms | -75ms | -9.32
| searchPostsInTeam | avg | 280ms | 260ms | -20ms | -7.14
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getSystemPing | p99 | 5ms | 0s | -5ms | -100.91
| channelMemberCountsByGroup | p99 | 92ms | 0s | -92ms | -100.49
| updateUserCustomStatus | p99 | 40ms | 5ms | -35ms | -88.04
| getClientLicense | p99 | 10ms | 5ms | -5ms | -52.04
| getRolesByNames | p99 | 98ms | 47ms | -51ms | -51.91
| getPrevTrialLicense | p99 | 98ms | 49ms | -49ms | -50.00
| getAnalytics | p99 | 485ms | 247ms | -238ms | -49.05
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 90ms | 8ms | 9.699
| BotStore.Get |  Avg| 6ms| 21ms | 15ms | 249.495
| |  P99| 43ms| 231ms | 188ms | 432.184
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 116ms| 116ms | 0s | 0.000
| |  P99| 431ms| 434ms | 3ms | 0.696
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 7ms | 1ms | 16.296
| |  P99| 66ms| 79ms | 13ms | 19.551
| ChannelStore.AnalyticsTypeCount |  Avg| 29ms| 14ms | -15ms | -51.053
| |  P99| 98ms| 25ms | -73ms | -74.462
| ChannelStore.Autocomplete |  Avg| 58ms| 61ms | 3ms | 5.179
| |  P99| 240ms| 241ms | 1ms | 0.416
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 124ms| 136ms | 12ms | 9.699
| |  P99| 2.485s| 3.658s | 1.173s | 47.203
| ChannelStore.CreateDirectChannel |  Avg| 70ms| 84ms | 14ms | 20.097
| |  P99| 709ms| 775ms | 66ms | 9.313
| ChannelStore.CreateInitialSidebarCategories |  Avg| 40ms| 48ms | 8ms | 19.860
| |  P99| 441ms| 483ms | 42ms | 9.531
| ChannelStore.CreateSidebarCategory |  Avg| 122ms| 151ms | 29ms | 23.761
| |  P99| 246ms| 248ms | 2ms | 0.815
| ChannelStore.Get |  Avg| 11ms| 14ms | 3ms | 26.648
| |  P99| 134ms| 185ms | 51ms | 38.109
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 30ms| 32ms | 2ms | 6.601
| |  P99| 231ms| 232ms | 1ms | 0.433
| ChannelStore.GetAllChannelMembersForUser |  Avg| 10ms| 12ms | 2ms | 19.427
| |  P99| 90ms| 97ms | 7ms | 7.768
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 28ms| 31ms | 3ms | 10.719
| |  P99| 240ms| 289ms | 49ms | 20.451
| ChannelStore.GetByName |  Avg| 8ms| 9ms | 1ms | 11.994
| |  P99| 89ms| 95ms | 6ms | 6.706
| ChannelStore.GetChannelUnread |  Avg| 9ms| 14ms | 5ms | 54.259
| |  P99| 94ms| 139ms | 45ms | 48.041
| ChannelStore.GetChannels |  Avg| 10ms| 12ms | 2ms | 19.870
| |  P99| 104ms| 156ms | 52ms | 49.974
| ChannelStore.GetChannelsByIds |  Avg| 9ms| 0s | -9ms | -96.038
| |  P99| 48ms| 0s | -48ms | -99.482
| ChannelStore.GetChannelsByUser |  Avg| 10ms| 12ms | 2ms | 20.187
| |  P99| 99ms| 133ms | 34ms | 34.400
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 11ms | 2ms | 22.793
| |  P99| 96ms| 133ms | 37ms | 38.471
| ChannelStore.GetFileCount |  Avg| 10ms| 13ms | 3ms | 29.321
| |  P99| 96ms| 137ms | 41ms | 42.905
| ChannelStore.GetGuestCount |  Avg| 8ms| 9ms | 1ms | 12.826
| |  P99| 91ms| 99ms | 8ms | 8.791
| ChannelStore.GetMember |  Avg| 10ms| 13ms | 3ms | 28.866
| |  P99| 97ms| 148ms | 51ms | 52.625
| ChannelStore.GetMemberCount |  Avg| 32ms| 34ms | 2ms | 6.227
| |  P99| 183ms| 205ms | 22ms | 11.993
| ChannelStore.GetMemberCountsByGroup |  Avg| 14ms| 0s | -14ms | -98.849
| |  P99| 91ms| 0s | -91ms | -99.938
| ChannelStore.GetMemberForPost |  Avg| 15ms| 17ms | 2ms | 13.235
| |  P99| 142ms| 181ms | 39ms | 27.396
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 7ms | 1ms | 17.978
| |  P99| 81ms| 89ms | 8ms | 9.826
| ChannelStore.GetMembers |  Avg| 4ms| 38ms | 34ms | 762.751
| |  P99| 10ms| 99ms | 89ms | 898.671
| ChannelStore.GetMembersForUser |  Avg| 11ms| 13ms | 2ms | 18.236
| |  P99| 100ms| 159ms | 59ms | 59.148
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 38ms | 28ms | 282.184
| |  P99| 47ms| 237ms | 190ms | 403.622
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 12ms | 3ms | 33.211
| |  P99| 98ms| 134ms | 36ms | 36.755
| ChannelStore.GetPublicChannelsForTeam |  Avg| 30ms| 32ms | 2ms | 6.741
| |  P99| 203ms| 204ms | 1ms | 0.492
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 24ms| 28ms | 4ms | 16.443
| |  P99| 222ms| 238ms | 16ms | 7.193
| ChannelStore.GetSidebarCategory |  Avg| 35ms| 32ms | -3ms | -8.503
| |  P99| 310ms| 430ms | 120ms | 38.706
| ChannelStore.GetTeamChannels |  Avg| 40ms| 31ms | -9ms | -22.235
| |  P99| 238ms| 226ms | -12ms | -5.042
| ChannelStore.IncrementMentionCount |  Avg| 8ms| 9ms | 1ms | 12.934
| |  P99| 89ms| 97ms | 8ms | 8.948
| ChannelStore.Save |  Avg| 46ms| 42ms | -4ms | -8.711
| |  P99| 441ms| 355ms | -86ms | -19.490
| ChannelStore.SaveMember |  Avg| 55ms| 62ms | 7ms | 12.790
| |  P99| 460ms| 495ms | 35ms | 7.611
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 16ms | 3ms | 23.444
| |  P99| 127ms| 178ms | 51ms | 40.033
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 12ms | 2ms | 19.499
| |  P99| 93ms| 100ms | 7ms | 7.523
| ChannelStore.UpdateSidebarCategories |  Avg| 150ms| 155ms | 5ms | 3.325
| |  P99| 932ms| 2.185s | 1.253s | 134.491
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 8ms| 10ms | 2ms | 24.245
| |  P99| 93ms| 96ms | 3ms | 3.233
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 13ms | 1ms | 8.414
| |  P99| 163ms| 186ms | 23ms | 14.111
| CommandWebhookStore.Cleanup |  Avg| 16ms| 12ms | -4ms | -24.298
| |  P99| 49ms| 25ms | -24ms | -48.979
| ComplianceStore.MessageExport |  Avg| 14ms| 18ms | 4ms | 28.942
| |  P99| 174ms| 228ms | 54ms | 31.124
| DraftStore.Delete |  Avg| 1ms| 2ms | 1ms | 67.532
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 20ms| 18ms | -2ms | -10.010
| |  P99| 217ms| 207ms | -10ms | -4.608
| DraftStore.Get |  Avg| 7ms| 22ms | 15ms | 201.579
| |  P99| 25ms| 25ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 28ms | 27ms | 1849.167
| |  P99| 5ms| 99ms | 94ms | 1898.990
| EmojiStore.GetByName |  Avg| 8ms| 10ms | 2ms | 23.636
| |  P99| 96ms| 103ms | 7ms | 7.260
| EmojiStore.GetMultipleByName |  Avg| 8ms| 7ms | -1ms | -12.127
| |  P99| 48ms| 24ms | -24ms | -49.485
| FileInfoStore.AttachToPost |  Avg| 19ms| 20ms | 1ms | 5.328
| |  P99| 207ms| 214ms | 7ms | 3.383
| FileInfoStore.Get |  Avg| 10ms| 12ms | 2ms | 21.009
| |  P99| 99ms| 150ms | 51ms | 51.353
| FileInfoStore.GetForPost |  Avg| 10ms| 12ms | 2ms | 20.574
| |  P99| 98ms| 167ms | 69ms | 70.059
| FileInfoStore.Save |  Avg| 13ms| 15ms | 2ms | 15.604
| |  P99| 98ms| 183ms | 85ms | 86.697
| FileInfoStore.SetContent |  Avg| 21ms| 26ms | 5ms | 24.166
| |  P99| 196ms| 230ms | 34ms | 17.347
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 6ms | 1ms | 20.573
| |  P99| 72ms| 89ms | 17ms | 23.562
| GroupStore.GetByName |  Avg| 5ms| 7ms | 2ms | 37.606
| |  P99| 80ms| 88ms | 8ms | 9.985
| GroupStore.GetGroups |  Avg| 9ms| 11ms | 2ms | 21.984
| |  P99| 94ms| 119ms | 25ms | 26.525
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 30ms| 7ms | -23ms | -75.712
| |  P99| 99ms| 25ms | -74ms | -74.747
| JobStore.Get |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 175ms| 186ms | 11ms | 6.291
| JobStore.GetAllByStatus |  Avg| 11ms| 13ms | 2ms | 18.764
| |  P99| 123ms| 176ms | 53ms | 43.149
| JobStore.GetAllByTypePage |  Avg| 10ms| 19ms | 9ms | 88.297
| |  P99| 90ms| 236ms | 146ms | 161.782
| JobStore.GetCountByStatusAndType |  Avg| 11ms| 8ms | -3ms | -27.521
| |  P99| 90ms| 145ms | 55ms | 61.453
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 6ms | -2ms | -25.280
| |  P99| 84ms| 90ms | 6ms | 7.117
| JobStore.Save |  Avg| 8ms| 9ms | 1ms | 12.668
| |  P99| 145ms| 66ms | -79ms | -54.483
| JobStore.UpdateOptimistically |  Avg| 12ms| 10ms | -2ms | -16.944
| |  P99| 97ms| 95ms | -2ms | -2.055
| JobStore.UpdateStatus |  Avg| 6ms| 12ms | 6ms | 93.841
| |  P99| 41ms| 199ms | 158ms | 383.027
| JobStore.UpdateStatusOptimistically |  Avg| 7ms| 9ms | 2ms | 28.840
| |  P99| 64ms| 147ms | 83ms | 130.705
| LicenseStore.GetAll |  Avg| 16ms| 18ms | 2ms | 12.268
| |  P99| 98ms| 49ms | -49ms | -50.255
| LinkMetadataStore.Get |  Avg| 8ms| 11ms | 3ms | 36.325
| |  P99| 95ms| 130ms | 35ms | 36.915
| LinkMetadataStore.Save |  Avg| 10ms| 15ms | 5ms | 51.707
| |  P99| 70ms| 327ms | 257ms | 367.132
| PluginStore.Delete |  Avg| 5ms| 6ms | 1ms | 20.120
| |  P99| 60ms| 79ms | 19ms | 31.648
| PluginStore.Get |  Avg| 4ms| 13ms | 9ms | 216.723
| |  P99| 24ms| 95ms | 71ms | 294.608
| PluginStore.List |  Avg| 9ms| 11ms | 2ms | 23.265
| |  P99| 87ms| 94ms | 7ms | 8.092
| PluginStore.SetWithOptions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 114ms| 149ms | 35ms | 30.729
| PostAcknowledgementStore.GetForPost |  Avg| 6ms| 9ms | 3ms | 47.818
| |  P99| 75ms| 95ms | 20ms | 26.592
| PostAcknowledgementStore.GetForPosts |  Avg| 11ms| 14ms | 3ms | 27.487
| |  P99| 177ms| 213ms | 36ms | 20.373
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 6ms | 2ms | 51.635
| |  P99| 24ms| 48ms | 24ms | 101.223
| PostPersistentNotificationStore.Get |  Avg| 5ms| 6ms | 1ms | 19.318
| |  P99| 44ms| 47ms | 3ms | 6.838
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 8ms | 1ms | 14.137
| |  P99| 86ms| 96ms | 10ms | 11.588
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 6ms| 0s | -6ms | -94.538
| |  P99| 24ms| 0s | -24ms | -98.959
| PostPriorityStore.GetForPost |  Avg| 7ms| 9ms | 2ms | 27.672
| |  P99| 120ms| 134ms | 14ms | 11.644
| PostPriorityStore.GetForPosts |  Avg| 11ms| 15ms | 4ms | 35.158
| |  P99| 179ms| 213ms | 34ms | 19.040
| PostStore.AnalyticsPostCount |  Avg| 488ms| 566ms | 78ms | 15.998
| |  P99| 990ms| 993ms | 3ms | 0.303
| PostStore.Delete |  Avg| 46ms| 68ms | 22ms | 47.647
| |  P99| 445ms| 855ms | 410ms | 92.131
| PostStore.Get |  Avg| 21ms| 25ms | 4ms | 19.203
| |  P99| 224ms| 238ms | 14ms | 6.242
| PostStore.GetEtag |  Avg| 10ms| 13ms | 3ms | 29.278
| |  P99| 108ms| 166ms | 58ms | 53.498
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 6ms | 1ms | 18.515
| |  P99| 69ms| 82ms | 13ms | 18.976
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 10ms | 2ms | 24.109
| |  P99| 92ms| 99ms | 7ms | 7.594
| PostStore.GetPostReminderMetadata |  Avg| 7ms| 18ms | 11ms | 161.260
| |  P99| 46ms| 174ms | 128ms | 280.550
| PostStore.GetPostReminders |  Avg| 10ms| 59ms | 49ms | 486.721
| |  P99| 87ms| 437ms | 350ms | 402.299
| PostStore.GetPosts |  Avg| 7ms| 8ms | 1ms | 14.659
| |  P99| 79ms| 90ms | 11ms | 14.009
| PostStore.GetPostsAfter |  Avg| 9ms| 11ms | 2ms | 21.956
| |  P99| 92ms| 108ms | 16ms | 17.327
| PostStore.GetPostsBefore |  Avg| 12ms| 14ms | 2ms | 16.765
| |  P99| 118ms| 169ms | 51ms | 43.125
| PostStore.GetPostsByIds |  Avg| 10ms| 0s | -10ms | -95.670
| |  P99| 49ms| 0s | -49ms | -100.504
| PostStore.GetPostsByThread |  Avg| 13ms| 16ms | 3ms | 22.399
| |  P99| 95ms| 114ms | 19ms | 20.014
| PostStore.GetPostsSince |  Avg| 24ms| 28ms | 4ms | 16.338
| |  P99| 203ms| 220ms | 17ms | 8.382
| PostStore.GetSingle |  Avg| 8ms| 10ms | 2ms | 24.758
| |  P99| 93ms| 124ms | 31ms | 33.259
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 33ms| 38ms | 5ms | 15.312
| |  P99| 343ms| 407ms | 64ms | 18.649
| PostStore.SearchPostsForUser |  Avg| 256ms| 231ms | -25ms | -9.750
| |  P99| 2.437s| 2.433s | -4ms | -0.164
| PostStore.SetPostReminder |  Avg| 16ms| 81ms | 65ms | 405.319
| |  P99| 225ms| 478ms | 253ms | 112.694
| PostStore.Update |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 385ms| 271ms | -114ms | -29.612
| PreferenceStore.DeleteCategoryAndName |  Avg| 28ms| 17ms | -11ms | -38.960
| |  P99| 445ms| 207ms | -238ms | -53.481
| PreferenceStore.Get |  Avg| 10ms| 12ms | 2ms | 20.210
| |  P99| 100ms| 152ms | 52ms | 52.158
| PreferenceStore.GetAll |  Avg| 7ms| 9ms | 2ms | 26.805
| |  P99| 92ms| 98ms | 6ms | 6.494
| PreferenceStore.Save |  Avg| 23ms| 26ms | 3ms | 12.929
| |  P99| 241ms| 248ms | 7ms | 2.908
| ProductNoticesStore.ClearOldNotices |  Avg| 25ms| 28ms | 3ms | 11.906
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 28ms | 26ms | 1400.829
| |  P99| 5ms| 50ms | 45ms | 908.415
| ProductNoticesStore.View |  Avg| 63ms| 73ms | 10ms | 15.848
| |  P99| 576ms| 783ms | 207ms | 35.913
| ReactionStore.GetForPost |  Avg| 8ms| 10ms | 2ms | 26.400
| |  P99| 85ms| 100ms | 15ms | 17.660
| RetentionPolicyStore.GetAll |  Avg| 4ms| 0s | -4ms | -108.195
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 2ms| 0s | -2ms | -98.481
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 18ms | 12ms | 211.277
| |  P99| 43ms| 213ms | 170ms | 393.842
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 15ms| 17ms | 2ms | 13.156
| |  P99| 199ms| 214ms | 15ms | 7.543
| SessionStore.GetLRUSessions |  Avg| 5ms| 6ms | 1ms | 18.660
| |  P99| 76ms| 86ms | 10ms | 13.177
| SessionStore.GetSessionsExpired |  Avg| 7ms| 18ms | 11ms | 154.623
| |  P99| 25ms| 237ms | 212ms | 860.913
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 9ms | 1ms | 13.331
| |  P99| 92ms| 106ms | 14ms | 15.251
| SessionStore.Remove |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 93ms| 93ms | 0s | 0.000
| SessionStore.Save |  Avg| 12ms| 14ms | 2ms | 16.383
| |  P99| 129ms| 170ms | 41ms | 31.678
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 12ms | 2ms | 20.469
| |  P99| 91ms| 98ms | 7ms | 7.712
| StatusStore.Get |  Avg| 5ms| 6ms | 1ms | 19.111
| |  P99| 79ms| 87ms | 8ms | 10.169
| StatusStore.GetByIds |  Avg| 12ms| 14ms | 2ms | 17.252
| |  P99| 145ms| 201ms | 56ms | 38.577
| StatusStore.SaveOrUpdate |  Avg| 15ms| 23ms | 8ms | 52.637
| |  P99| 211ms| 248ms | 37ms | 17.500
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 19ms | 10ms | 107.702
| |  P99| 87ms| 212ms | 125ms | 143.678
| StatusStore.UpdateLastActivityAt |  Avg| 9ms| 11ms | 2ms | 21.932
| |  P99| 92ms| 98ms | 6ms | 6.553
| SystemStore.GetByName |  Avg| 6ms| 7ms | 1ms | 17.313
| |  P99| 78ms| 89ms | 11ms | 14.036
| TeamStore.AnalyticsTeamCount |  Avg| 19ms| 18ms | -1ms | -5.347
| |  P99| 98ms| 97ms | -1ms | -1.026
| TeamStore.Get |  Avg| 7ms| 10ms | 3ms | 40.687
| |  P99| 91ms| 110ms | 19ms | 20.881
| TeamStore.GetActiveMemberCount |  Avg| 66ms| 69ms | 3ms | 4.517
| |  P99| 99ms| 238ms | 139ms | 139.728
| TeamStore.GetAllPage |  Avg| 6ms| 8ms | 2ms | 32.163
| |  P99| 86ms| 97ms | 11ms | 12.792
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 7ms| 9ms | 2ms | 27.681
| |  P99| 90ms| 96ms | 6ms | 6.684
| TeamStore.GetMany |  Avg| 6ms| 0s | -6ms | -97.113
| |  P99| 24ms| 0s | -24ms | -100.209
| TeamStore.GetMember |  Avg| 3ms| 4ms | 1ms | 32.083
| |  P99| 42ms| 56ms | 14ms | 33.650
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 8ms | 1ms | 15.155
| |  P99| 89ms| 98ms | 9ms | 10.156
| TeamStore.GetTeamsForUser |  Avg| 7ms| 8ms | 1ms | 14.440
| |  P99| 90ms| 94ms | 4ms | 4.458
| TeamStore.GetTotalMemberCount |  Avg| 68ms| 62ms | -6ms | -8.869
| |  P99| 238ms| 226ms | -12ms | -5.042
| TeamStore.SaveMember |  Avg| 42ms| 46ms | 4ms | 9.540
| |  P99| 245ms| 293ms | 48ms | 19.590
| ThreadStore.Get |  Avg| 8ms| 9ms | 1ms | 12.293
| |  P99| 91ms| 93ms | 2ms | 2.207
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 10ms | 2ms | 24.956
| |  P99| 94ms| 128ms | 34ms | 36.346
| ThreadStore.GetTeamsUnreadForUser |  Avg| 10ms| 12ms | 2ms | 19.255
| |  P99| 141ms| 173ms | 32ms | 22.727
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 10ms | 2ms | 24.239
| |  P99| 93ms| 109ms | 16ms | 17.120
| ThreadStore.GetThreadForUser |  Avg| 16ms| 20ms | 4ms | 24.361
| |  P99| 199ms| 221ms | 22ms | 11.036
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 15ms| 18ms | 3ms | 19.611
| |  P99| 100ms| 135ms | 35ms | 35.082
| ThreadStore.GetThreadsForUser |  Avg| 12ms| 15ms | 3ms | 24.202
| |  P99| 121ms| 173ms | 52ms | 43.128
| ThreadStore.GetTotalThreads |  Avg| 7ms| 9ms | 2ms | 28.814
| |  P99| 86ms| 98ms | 12ms | 13.906
| ThreadStore.GetTotalUnreadMentions |  Avg| 7ms| 9ms | 2ms | 27.202
| |  P99| 87ms| 100ms | 13ms | 15.012
| ThreadStore.GetTotalUnreadThreads |  Avg| 7ms| 9ms | 2ms | 28.610
| |  P99| 87ms| 99ms | 12ms | 13.832
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 7ms| 9ms | 2ms | 26.930
| |  P99| 87ms| 99ms | 12ms | 13.834
| ThreadStore.MaintainMembership |  Avg| 19ms| 23ms | 4ms | 20.819
| |  P99| 224ms| 236ms | 12ms | 5.356
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 11ms | 1ms | 10.182
| |  P99| 96ms| 122ms | 26ms | 27.140
| ThreadStore.MarkAllAsReadByTeam |  Avg| 10ms| 23ms | 13ms | 125.932
| |  P99| 49ms| 98ms | 49ms | 100.001
| ThreadStore.MarkAsRead |  Avg| 9ms| 11ms | 2ms | 22.173
| |  P99| 84ms| 96ms | 12ms | 14.278
| ThreadStore.UpdateMembership |  Avg| 9ms| 11ms | 2ms | 22.960
| |  P99| 87ms| 95ms | 8ms | 9.164
| TokenStore.Cleanup |  Avg| 15ms| 29ms | 14ms | 93.386
| |  P99| 49ms| 98ms | 49ms | 99.999
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 61ms | -21ms | -25.610
| UserStore.AnalyticsActiveCount |  Avg| 59ms| 47ms | -12ms | -20.441
| |  P99| 244ms| 99ms | -145ms | -59.426
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 8ms| 5ms | -3ms | -39.061
| |  P99| 25ms| 24ms | -1ms | -4.073
| UserStore.AutocompleteUsersInChannel |  Avg| 71ms| 77ms | 6ms | 8.441
| |  P99| 359ms| 399ms | 40ms | 11.130
| UserStore.Count |  Avg| 31ms| 25ms | -6ms | -19.276
| |  P99| 98ms| 207ms | 109ms | 111.098
| UserStore.Get |  Avg| 6ms| 7ms | 1ms | 18.130
| |  P99| 82ms| 93ms | 11ms | 13.419
| UserStore.GetAllProfiles |  Avg| 6ms| 7ms | 1ms | 15.516
| |  P99| 56ms| 76ms | 20ms | 35.608
| UserStore.GetAllProfilesInChannel |  Avg| 439ms| 467ms | 28ms | 6.376
| |  P99| 2.247s| 2.334s | 87ms | 3.871
| UserStore.GetByUsername |  Avg| 9ms| 16ms | 7ms | 78.077
| |  P99| 88ms| 192ms | 104ms | 118.100
| UserStore.GetForLogin |  Avg| 6ms| 7ms | 1ms | 16.296
| |  P99| 83ms| 93ms | 10ms | 12.024
| UserStore.GetMany |  Avg| 14ms| 7ms | -7ms | -49.275
| |  P99| 94ms| 83ms | -11ms | -11.640
| UserStore.GetProfileByIds |  Avg| 11ms| 13ms | 2ms | 18.782
| |  P99| 113ms| 165ms | 52ms | 46.156
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 13ms | 3ms | 29.314
| |  P99| 100ms| 158ms | 58ms | 58.013
| UserStore.GetProfilesInChannel |  Avg| 161ms| 178ms | 17ms | 10.561
| |  P99| 490ms| 491ms | 1ms | 0.204
| UserStore.GetProfilesNotInChannel |  Avg| 9ms| 21ms | 12ms | 135.881
| |  P99| 48ms| 226ms | 178ms | 370.833
| UserStore.GetUnreadCount |  Avg| 8ms| 11ms | 3ms | 37.936
| |  P99| 89ms| 125ms | 36ms | 40.371
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 45ms | 4ms | 9.759
| UserStore.Save |  Avg| 88ms| 91ms | 3ms | 3.428
| |  P99| 365ms| 419ms | 54ms | 14.786
| UserStore.Search |  Avg| 52ms| 56ms | 4ms | 7.673
| |  P99| 232ms| 240ms | 8ms | 3.442
| UserStore.Update |  Avg| 22ms| 24ms | 2ms | 8.976
| |  P99| 210ms| 224ms | 14ms | 6.659
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 9ms | 1ms | 12.486
| |  P99| 81ms| 92ms | 11ms | 13.517
| UserStore.UpdateLastLogin |  Avg| 8ms| 9ms | 1ms | 12.663
| |  P99| 65ms| 84ms | 19ms | 29.407
| UserStore.UpdateUpdateAt |  Avg| 8ms| 9ms | 1ms | 12.793
| |  P99| 72ms| 79ms | 7ms | 9.752
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 7ms | 1ms | 18.094
| |  P99| 81ms| 89ms | 8ms | 9.879
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 14ms | 2ms | 16.471
| |  P99| 139ms| 181ms | 42ms | 30.302
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 616ms| 697ms | 81ms | 13.146
| | P99| 2.497s| 4.284s | 1.787s | 71.559
| addTeamMember | Avg| 1.364s| 1.484s | 120ms | 8.796
| | P99| 7.702s| 8.856s | 1.154s | 14.982
| autocompleteChannelsForTeamForSearch | Avg| 124ms| 137ms | 13ms | 10.498
| | P99| 2.485s| 3.658s | 1.173s | 47.203
| autocompleteUsers | Avg| 63ms| 69ms | 6ms | 9.582
| | P99| 318ms| 378ms | 60ms | 18.881
| channelMemberCountsByGroup | Avg| 15ms| 0s | -15ms | -100.610
| | P99| 92ms| 0s | -92ms | -100.491
| createCategoryForTeamForUser | Avg| 129ms| 157ms | 28ms | 21.701
| | P99| 248ms| 248ms | 0s | 0.000
| createChannel | Avg| 804ms| 729ms | -75ms | -9.325
| | P99| 4.6s| 4.6s | 0s | 0.000
| createDirectChannel | Avg| 752ms| 827ms | 75ms | 9.974
| | P99| 3.216s| 4.466s | 1.25s | 38.865
| createGroupChannel | Avg| 1.183s| 1.241s | 58ms | 4.903
| | P99| 4.842s| 7.4s | 2.558s | 52.833
| createPost | Avg| 804ms| 928ms | 124ms | 15.429
| | P99| 4.608s| 4.861s | 253ms | 5.491
| createUser | Avg| 322ms| 354ms | 32ms | 9.941
| | P99| 2.182s| 2.349s | 167ms | 7.654
| deleteDraft | Avg| 5ms| 13ms | 8ms | 151.259
| | P99| 25ms| 25ms | 0s | 0.000
| deletePost | Avg| 77ms| 112ms | 35ms | 45.685
| | P99| 445ms| 2.065s | 1.62s | 364.030
| followThreadByUser | Avg| 60ms| 51ms | -9ms | -14.898
| | P99| 244ms| 433ms | 189ms | 77.340
| getAllTeams | Avg| 8ms| 10ms | 2ms | 24.827
| | P99| 103ms| 159ms | 56ms | 54.352
| getAnalytics | Avg| 77ms| 128ms | 51ms | 66.255
| | P99| 485ms| 247ms | -238ms | -49.048
| getCategoriesForTeamForUser | Avg| 25ms| 29ms | 4ms | 15.925
| | P99| 227ms| 241ms | 14ms | 6.175
| getChannel | Avg| 29ms| 38ms | 9ms | 31.418
| | P99| 249ms| 314ms | 65ms | 26.120
| getChannelMember | Avg| 23ms| 27ms | 4ms | 17.241
| | P99| 237ms| 273ms | 36ms | 15.204
| getChannelMembers | Avg| 6ms| 63ms | 57ms | 1022.755
| | P99| 10ms| 246ms | 236ms | 2382.992
| getChannelMembersForTeamForUser | Avg| 12ms| 14ms | 2ms | 16.866
| | P99| 130ms| 182ms | 52ms | 39.935
| getChannelMembersForUser | Avg| 8ms| 38ms | 30ms | 372.991
| | P99| 10ms| 238ms | 228ms | 2290.583
| getChannelStats | Avg| 6ms| 7ms | 1ms | 16.569
| | P99| 97ms| 128ms | 31ms | 31.979
| getChannelUnread | Avg| 11ms| 16ms | 5ms | 45.733
| | P99| 115ms| 174ms | 59ms | 51.471
| getChannelsForTeamForUser | Avg| 11ms| 14ms | 3ms | 26.280
| | P99| 148ms| 184ms | 36ms | 24.292
| getChannelsForUser | Avg| 10ms| 13ms | 3ms | 29.040
| | P99| 125ms| 152ms | 27ms | 21.559
| getClientConfig | Avg| 19ms| 22ms | 3ms | 15.791
| | P99| 232ms| 246ms | 14ms | 6.032
| getClientLicense | Avg| 1ms| 0s | -1ms | -80.358
| | P99| 10ms| 5ms | -5ms | -52.043
| getFilePreview | Avg| 64ms| 69ms | 5ms | 7.776
| | P99| 324ms| 392ms | 68ms | 20.987
| getFileThumbnail | Avg| 52ms| 57ms | 5ms | 9.594
| | P99| 250ms| 344ms | 94ms | 37.675
| getFilteredUsersStats | Avg| 30ms| 50ms | 20ms | 67.590
| | P99| 98ms| 246ms | 148ms | 151.016
| getGroups | Avg| 8ms| 15ms | 7ms | 84.592
| | P99| 25ms| 49ms | 24ms | 97.077
| getGroupsAssociatedToChannelsByTeam | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 10ms| 25ms | 15ms | 150.696
| getJobsByType | Avg| 11ms| 19ms | 8ms | 75.371
| | P99| 90ms| 236ms | 146ms | 161.782
| getPostThread | Avg| 50ms| 64ms | 14ms | 28.185
| | P99| 457ms| 495ms | 38ms | 8.323
| getPostsForChannel | Avg| 93ms| 114ms | 21ms | 22.649
| | P99| 995ms| 1.533s | 538ms | 54.060
| getPostsForChannelAroundLastUnread | Avg| 41ms| 48ms | 7ms | 16.965
| | P99| 462ms| 497ms | 35ms | 7.580
| getPreferences | Avg| 8ms| 10ms | 2ms | 24.747
| | P99| 97ms| 127ms | 30ms | 30.819
| getPrevTrialLicense | Avg| 21ms| 23ms | 2ms | 9.650
| | P99| 98ms| 49ms | -49ms | -49.998
| getProfileImage | Avg| 87ms| 86ms | -1ms | -1.155
| | P99| 471ms| 476ms | 5ms | 1.062
| getPublicChannelsForTeam | Avg| 31ms| 34ms | 3ms | 9.528
| | P99| 203ms| 209ms | 6ms | 2.951
| getRolesByNames | Avg| 20ms| 2ms | -18ms | -89.633
| | P99| 98ms| 47ms | -51ms | -51.908
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getSystemPing | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.914
| getTeamMember | Avg| 10ms| 13ms | 3ms | 29.447
| | P99| 97ms| 168ms | 71ms | 73.559
| getTeamMembersForUser | Avg| 9ms| 11ms | 2ms | 21.521
| | P99| 145ms| 173ms | 28ms | 19.345
| getTeamStats | Avg| 85ms| 98ms | 13ms | 15.365
| | P99| 242ms| 460ms | 218ms | 90.013
| getTeamsForUser | Avg| 7ms| 8ms | 1ms | 14.271
| | P99| 93ms| 103ms | 10ms | 10.734
| getTeamsUnreadForUser | Avg| 14ms| 17ms | 3ms | 21.103
| | P99| 206ms| 220ms | 14ms | 6.810
| getThreadsForUser | Avg| 13ms| 16ms | 3ms | 23.072
| | P99| 154ms| 193ms | 39ms | 25.272
| getUser | Avg| 13ms| 16ms | 3ms | 22.621
| | P99| 226ms| 243ms | 17ms | 7.524
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 40ms| 56ms | 16ms | 40.039
| getUsers | Avg| 14ms| 16ms | 2ms | 14.441
| | P99| 222ms| 236ms | 14ms | 6.310
| getUsersByIds | Avg| 3ms| 4ms | 1ms | 31.273
| | P99| 43ms| 52ms | 9ms | 20.707
| getUsersByNames | Avg| 11ms| 13ms | 2ms | 18.396
| | P99| 124ms| 174ms | 50ms | 40.265
| getWebappPlugins | Avg| 0s| 1ms | 1ms | 246.902
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 216ms| 230ms | 14ms | 6.488
| | P99| 2.082s| 2.221s | 139ms | 6.677
| logout | Avg| 171ms| 173ms | 2ms | 1.166
| | P99| 860ms| 855ms | -5ms | -0.581
| patchPost | Avg| 105ms| 1.015s | 910ms | 867.906
| | P99| 885ms| 10s | 9.115s | 1029.961
| removeUserCustomStatus | Avg| 436ms| 469ms | 33ms | 7.561
| | P99| 2.029s| 2.306s | 277ms | 13.653
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 34ms| 39ms | 5ms | 14.680
| | P99| 291ms| 373ms | 82ms | 28.145
| searchAllChannels | Avg| 59ms| 62ms | 3ms | 5.099
| | P99| 241ms| 243ms | 2ms | 0.829
| searchGroupChannels | Avg| 13ms| 17ms | 4ms | 30.084
| | P99| 144ms| 194ms | 50ms | 34.799
| searchPostsInTeam | Avg| 280ms| 260ms | -20ms | -7.144
| | P99| 2.487s| 2.483s | -4ms | -0.161
| searchUsers | Avg| 55ms| 59ms | 4ms | 7.299
| | P99| 236ms| 243ms | 7ms | 2.966
| setPostReminder | Avg| 53ms| 200ms | 147ms | 278.767
| | P99| 242ms| 2.11s | 1.868s | 773.499
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 47ms| 57ms | 10ms | 21.231
| | P99| 411ms| 435ms | 24ms | 5.845
| updateCategoriesForTeamForUser | Avg| 231ms| 231ms | 0s | 0.000
| | P99| 967ms| 2.29s | 1.323s | 136.862
| updatePreferences | Avg| 38ms| 46ms | 8ms | 20.853
| | P99| 380ms| 405ms | 25ms | 6.571
| updateReadStateAllThreadsByUser | Avg| 10ms| 23ms | 13ms | 124.925
| | P99| 49ms| 98ms | 49ms | 100.001
| updateReadStateThreadByUser | Avg| 125ms| 150ms | 25ms | 20.034
| | P99| 892ms| 963ms | 71ms | 7.958
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -69.924
| | P99| 40ms| 5ms | -35ms | -88.038
| uploadFileStream | Avg| 486ms| 510ms | 24ms | 4.934
| | P99| 2.205s| 2.314s | 109ms | 4.944
| upsertDraft | Avg| 2ms| 17ms | 15ms | 871.939
| | P99| 5ms| 98ms | 93ms | 1877.287
| viewChannel | Avg| 39ms| 49ms | 10ms | 25.321
| | P99| 424ms| 467ms | 43ms | 10.148
